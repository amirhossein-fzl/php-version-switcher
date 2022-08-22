## What PHP Version Switcher ( psv )
PHP Version Switcher ( psv ) a shell script that allows you to switch between different versions of php. **This script is made for Linux**.

## Getting Started
To use this script, follow these steps:

first clone this repository with these command:

    git clone ...

You need to configure the php versions installed on the OS. Edit the `pvs` file with the following command and in the beginning lines, in the php_versions array, add the php versions installed in your OS, as in the example in the `pvs` file.

    nano ./pvs

Save file and copy `pvs` file to path `/usr/lib/bin` with these command:

    sudo cp ./pvs /usr/lib/bin
Use and Enjoy!

    sudo psv

