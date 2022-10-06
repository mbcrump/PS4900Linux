## Reason for the Repo

There are a number of BD-JB ISO images and payloads floating around on mega.nz and other places that could be removed at any moment. I took the time to archive them here for future research. 

I have a recent videos that shows how to use the recent 4.03 BD-JB and the PS5 FTP Payload that might help.  

- [Setting up an FTP Server and viewing PS5 Game Disks with BD-JB on PS5 4.03](https://www.youtube.com/watch?v=mhR5FFUAmNU)

## PS5 4.03 BD-JB related ISOs / Payloads 
|Filename   	|Description   	|
|---	|---	|
|[ps5-listdir-root.iso](https://github.com/mbcrump/PS4900Linux/blob/main/bd-j/isos/ps5-listdir-root.iso)   	|PS5 rootvnode listdir PoC Released by sleirsgoevy on 10/03   	|
|[bd-jb-ps5-payload.iso](https://github.com/mbcrump/PS4900Linux/blob/main/bd-j/isos/bd-jb-ps5-payload.iso)   	|BD-JB w/ payload support (port 9019)(Released by sleirsgoevy on 10/04   	|
|[bd-jb-ps5-payload-2.iso](https://github.com/mbcrump/PS4900Linux/blob/main/bd-j/isos/bd-jb-ps5-payload-2.iso)   	|Updated payload server, cleans up Released by sleirsgoevy on 10/05   	|
|[ps5ftppayload.bin](https://github.com/mbcrump/PS4900Linux/blob/main/bd-j/isos/ps5ftppayload.bin)   	|PS5 FTP Payload for 4.03 Released by SiSTRO and Control Execute   	|

## Prior to the PS5 4.03 BD-JB 

|Filename   	|Description   	|
|---	|---	|
|[Doom-BluPlay.iso](https://github.com/mbcrump/PS4900Linux/blob/main/bd-j/isos/Doom-BluPlay.iso)   	|Not an exploit but a way to play Doom on compatible consoles (Xbox, PS4, PS5, etc.)   	|
|[bd-jb.iso](https://github.com/mbcrump/PS4900Linux/blob/main/bd-j/isos/bd-jb.iso)   	|sleirsgoevy original implementation - it waits for a payload   	|
|[bd-jb-v2.iso](https://github.com/mbcrump/PS4900Linux/blob/main/bd-j/isos/bd-jb-v2.iso)   	|The 6/20 release from sleirsgoevy - it waits for a payload   	|
|[bd-jb-ps5.iso](https://github.com/mbcrump/PS4900Linux/blob/main/bd-j/isos/bd-jb-ps5.iso)   	|The 8/13 release from sleirsgoevy - it lists app0 and /   	|
|[ret.bin](https://github.com/mbcrump/PS4900Linux/blob/main/bd-j/isos/ret.bin)   	|Payload that returns "Hello World"   	|
|[notify.bin](https://github.com/mbcrump/PS4900Linux/blob/main/bd-j/isos/notify.bin)/[notification.elf](https://github.com/mbcrump/PS4900Linux/blob/main/bd-j/isos/notification.elf)   	|Payload that pops a notification box - use either 	|
|[ftp.bin](https://github.com/mbcrump/PS4900Linux/blob/main/bd-j/isos/ftp.bin)/[ftp.elf](https://github.com/mbcrump/PS4900Linux/blob/main/bd-j/isos/bd-jb/ftp.elf)   	|Payload that creates an FTP Server - SiSTRO version that auto-resolves IP 	|
|[ftp-v2.bin](https://github.com/mbcrump/PS4900Linux/blob/main/bd-j/isos/ftp-v2.bin)   	|Payload that creates an FTP Server that works on 9.00 with the 6.20 sleirsgoevy iso - 06-26-22 version 	|
|[ftp-manual.bin](https://github.com/mbcrump/PS4900Linux/blob/main/bd-j/isos/ftp-manual.bin)/[ftp-manual.elf](https://github.com/mbcrump/PS4900Linux/blob/main/bd-j/isos/bd-jb/ftp-manual.elf)   	|Payload that creates an FTP Server - ORIGINAL version that requires manual IP configuration 	|
|[bigboss.iso](https://github.com/mbcrump/PS4900Linux/blob/main/bd-j/isos/bigboss.iso)   	|bigboss implementation - it waits for a payload  	|
|[sample.iso](https://github.com/mbcrump/PS4900Linux/blob/main/bd-j/isos/sample.iso)   	|Returns file listing automatically without sending a payload    	|
|[Minimal BD-J (Java) Devkit for PS3.zip](https://github.com/mbcrump/PS4900Linux/blob/main/bd-j/isos/Minimal%20BD-J%20(Java)%20Devkit%20for%20PS3.zip)   	|Used to create compatible BD-J images (not using the exploit)   	|
|[ps5-lua-server.iso](https://github.com/mbcrump/PS4900Linux/blob/main/bd-j/isos/ps5-lua-server.iso)   	|LUA Server for PS5 BD-J (use [scripts](https://github.com/mbcrump/PS4900Linux/tree/main/bd-j/isos/scripts) folder for samples)    	|

Burn .ISO files with https://www.imgburn.com/

Notes:

Official bd-j repo: https://github.com/psxdev/bd-jb

This does **NOT** work with DVDs. https://twitter.com/Sameer01988388/status/1538157532220248065

Xbox Implementation - https://twitter.com/Shykelit1/status/1538413703778881537

To send payloads use https://github.com/valentinbreiz/PS4-Payload-Sender/releases/tag/1.1
