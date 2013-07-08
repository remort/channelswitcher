It's better to run the script with 'openvt' command after all system services are loaded at the end of your /etc/rc.local file. Like this:

#contents of your rc.local script goes above
openvt -c 8 -- switcher
exit 0