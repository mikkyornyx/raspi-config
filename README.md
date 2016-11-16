# raspi-config
Configuration tool for the Raspberry Pi.

Difference with default Raspberry Pi raspi-config tool is that this one uses non-interactive mode and hopefully will have more functions.

# installation

To install this script locally, cd to working directory and execute command:

git clone https://github.com/mikkyornyx/raspi-config

# usage

For usage, currently these options are supported in noninteractive mode: --expand-rootfs, --set-timezone, --set-hostname. Each command should
be run in super-user rights, sudo is enough. Before changing timezone, apply 755 permissions to /etc/timezone file. Command should be superceded
with arguments.

# examples

* sudo raspi-config/raspi-config --set-hostname=ubuntu.local 

* sudo raspi-config/raspi-config --set-timezone=Asia/Vladivostok

* sudo raspi-config/raspi-config --expand-rootfs
