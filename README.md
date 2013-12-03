Crestron Module for Plex Home Theater
=====================================

Description
-----------
This module allows any ethernet-equipped Crestron 2-series processor to control a Plex Home Theater client. Before implementing this module you should have Plex Media Server and Plex Home Theater installed and running. Make sure port 3005 is open and not blocked by any firewall on the IP Address where Plex Home Theater resides. 

This module requires one Crestron TCP/IP Client connection. Set the IP address of this client to the IP address of your Plex Home Theater instance. The default port is 3005


Version History
----------------
v1.3
Rewrote module to utilize JSON protocol for upcoming Plex/Home Theater application. Several functions have been removed from this version but may be added back in a later version.


v1.2
Added Commands
 + Jump To: Home
 + Jump To: Now Playing
 + Jump To: Now Playing Queue
 + Add to: Now Playing Queue
 + Now Playing: Tech Info
 + Now Playing: Info
 + Now Playing: Transport Menu
 + Now Playing: View Mode     
 + Now Playing: Subtitle Track
 + Now Playing: Audio Track

v1.1 
Bug Fixes
 + Cursor Up/Down/Left/Right accidental double issue because of osc timing. (Press and Hold now used along with osc) 
 + Page Up/Down accidental double issue because of osc timing. (Press and Hold now used along with osc) 

v1.0
 + Inital Release

