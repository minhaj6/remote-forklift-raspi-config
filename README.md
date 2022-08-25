# remote-forklift-raspi-config
A few raspberry pi configuration files for remote-forklift project


Symlink (with absolute path) to correct locations. Systemd service file locations are commented in the unit files.


`sudo ln -s /home/remote-forklift-raspi-config/90-mhrobot.rules /etc/udev/rules.d/`


Install ROS Noetic and mavproxy for this to work properly.
