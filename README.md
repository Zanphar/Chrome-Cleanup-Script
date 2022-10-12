# Chrome OS Cleanup Script (based on the "Ubuntu Cleanup Script")
This continues to provide much of the original work from its author, while also adding additional code to avoid nonroot users from executing this, as well as the removal and re-creation of the /tmp directory. *Snap has been installed on my system, but still causes an error.*

# Linux Development Enviorment
*This must be enabled on your system for it to be used.* This being 2022, there's absolutely no reason for such small storage on CHrombooks; even the largest provides next to no space for the installation and use of software. Yes, I am aware it's mostly a cloud-based platform, but you can install many mobile apps ranging from Android to Chrome OS to Linux; it's silly that we cannot install to MicroSD; USB Storage, External Storage or provide larger space on these devices. So in short terms, *"Space is too short, let's not waste it!"*

*Please note, the original version is "clean.sh", the modified version by me is ucln.sh"*.

# Ubuntu Cleanup Script
This script removes unneeded files and libraries, including log files and snaps. I originally created it to combat the /var directory filling up (when on a seperate partition). I know there is redundency with apt vs apt-get commands, but I always seem to have more drive space after running both!  I created this for Ubuntu 18.04 (Desktop), but it should run on other distros based on Ubuntu without issue.

To run this script from anywhere, place it in your `/usr/local/bin directory`

To list your partition sizes run `df -Th | sort`
