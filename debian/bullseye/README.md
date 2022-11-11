# Debian Bullseye

Debian Bullseye preseeds 🌱

## Server

Click [here](server.cfg) to get the preseed file.

Assumptions:

- You have x86 architecture
- You have a working internet connection
- You want to use English locale
- You want to use US keyboard layout
- You want to use UTC timezone
- You don't want to create root account
- You want to use LVM
- You don't want to encrypt your disk
- You don't want a desktop environment

## Usage

You can use preseeds to automate the installation of Debian.
They are used to automatically answer questions
that would otherwise be asked during the installation process.
Preseeds in this repository contain what I consider to be sensible defaults.
The installation is not fully automated,
as you still need to manually answer some specific questions
(like user account creation).

To use a preseed, you need to pass it to the installer.
See [Debian documentation](https://wiki.debian.org/DebianInstaller/Preseed)
for more details and possible options.
I recommend using the [netboot.xyz](https://netboot.xyz) installer.
After booting and choosing Debian,
you will have an option to specify a preseed URL.
