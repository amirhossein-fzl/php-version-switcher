## What PHP Version Switcher ( pvs )
PHP Version Switcher ( pvs ) a shell script that allows you to switch between different versions of php. **This script is made for Debian and Debian-based distro's**.

## Getting Started
To use this script, follow these steps:

first clone this repository with these command:

    git clone https://github.com/amirhossein-fzl/php-version-switcher.git

You need to configure the php versions installed on the OS. Edit the `pvs` file with the following command and in the beginning lines, in the php_versions array, add the php versions installed in your OS, as in the example in the `pvs` file.

    nano ./pvs

Save file and copy `pvs` file to path `/usr/bin` with these command:

    sudo cp ./pvs /usr/bin
Use and Enjoy!

    sudo pvs

