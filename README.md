# Autostart Script for Linux Teamspeak 3 Server

# What to do?
## Create File
`nano /etc/init.d/teamspeak3`

## Change permissions
`chmod 755 /etc/init.d/teamspeak3`

## Define in Autostart
`update-rc.d teamspeak3 defaults`

## Available Options
Start: `/etc/init.d/teamspeak3 start`<br>
Stop: `/etc/init.d/teamspeak3 stop`<br>
Status: `/etc/init.d/teamspeak3 status`<br>
Restart: `/etc/init.d/teamspeak3 restart`

