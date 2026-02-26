Use the fancontrol script (https://raw.githubusercontent.com/lm-sensors/lm-sensors/master/prog/pwm/fancontrol)
We will run the script from the /root directory since it has exec privileges.

Copy the above configuration file to /etc/fancontrol

Add the service file to /etc/systemd/system/fancontrol.service

enable and start—make sure things are working as expected.
