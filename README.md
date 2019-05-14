# openstagelistener
# This project listens for messages to MyPortal, a software for the unify Openscape Telephone systems and can do stuff depending on the status of the ip telephone.
Author: Name <mark.now@web.de>
(c) 2019 Markus Nowatzki
v0.1
GPL-3.0-or-later
This program comes with ABSOLUTELY NO WARRANTY; 
This is free software, and you are welcome to redistribute it
under certain conditions; 

I do not have the time to develop any further, maybe someone wants to use this and make it simpler ;-)

This project listens for messages to MyPortal, a software for the unify Openscape Telephone systems and can do stuff depending on the dstatus of the telephone.


This project is still very raw and is currently working on my machine.
Please check all paths and icons, etc.

It needs to run via sudo, because of ngrep

The following software is necessary:

- myportal - for receiving phone messages
- yad - for creating tray icon
- ngrep - for listening to the messages that myportal receives 
- ssh daemon on target machine
- ssh client on client machine
