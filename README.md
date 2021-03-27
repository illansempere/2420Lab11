# 2420Lab11

To Install the Weather Timer:

1. Copy and paste the three files in a folder named "week11" in your home directory.
2. Copy weather.timer and weather.service to /etc/systemd/system/ by running "sudo cp weather.timer /etc/systemd/system/" and "sudo cp weather.service /etc/systemd/system/".
3. Refresh by running "sudo systemctl daemon-reload".
4. Activate both units with "sudo systemctl start weather.timer" and "sudo systemctl start weather.service".
