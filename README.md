# debian11-unattended

A collection of various configs and scripts I use to automate my server setup (using Debian 11) as much as possible. Solutions might have been found from other sources (forums, websites, other repos) or created by me.

If I find something useful I'll try to remember linking source.

# Current state

Current preseed configuration works as expected from pressing Install to 100% done, however it does print this error for a few seconds in the beginning;

`````mount: mounting /dev/sda on /media failed: Invalid argument
umount: can't unmount /media: Invalid argument
mount: mounting /dev/sda on /media failed: Invalid argument````

# Improvements
- Solve/remove above mentioned errors
- Remove the need to press "Install" in the menu
- Automatically encrypt given password from .env or similar
`````
