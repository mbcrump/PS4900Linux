The ISO images floating around for BD-J implementation. 

Watch the [video](https://www.youtube.com/watch?v=8jEG-pq2sXs) if you want a further explanation of the ISO images and payloads mentioned below.

|Filename   	|Description   	|
|---	|---	|
|[Doom-BluPlay.iso](https://github.com/mbcrump/PS4900Linux/blob/main/bd-j/isos/Doom-BluPlay.iso)   	|Not an exploit but a way to play Doom on compatible consoles (Xbox, PS4, PS5, etc.)   	|
|[bd-jb.iso](https://github.com/mbcrump/PS4900Linux/blob/main/bd-j/isos/bd-jb.iso)   	|sleirsgoevy original implementation - it waits for a payload   	|
|[bd-jb-v2.iso](https://github.com/mbcrump/PS4900Linux/blob/main/bd-j/isos/bd-jb-v2.iso)   	|The 6/20 release from sleirsgoevy - it waits for a payload   	|
|[ret.bin](https://github.com/mbcrump/PS4900Linux/blob/main/bd-j/isos/ret.bin)   	|Payload that returns "Hello World"   	|
|[notify.bin](https://github.com/mbcrump/PS4900Linux/blob/main/bd-j/isos/notify.bin)/[notification.elf](https://github.com/mbcrump/PS4900Linux/blob/main/bd-j/isos/notification.elf)   	|Payload that pops a notification box - use either 	|
|[ftp.bin](https://github.com/mbcrump/PS4900Linux/blob/main/bd-j/isos/ftp.bin)/[ftp.elf](https://github.com/mbcrump/PS4900Linux/blob/main/bd-j/isos/bd-jb/ftp.elf)   	|Payload that creates an FTP Server - SiSTRO version that auto-resolves IP 	|
|[bigboss.iso](https://github.com/mbcrump/PS4900Linux/blob/main/bd-j/isos/bigboss.iso)   	|bigboss implementation - it waits for a payload  	|
|[sample.iso](https://github.com/mbcrump/PS4900Linux/blob/main/bd-j/isos/sample.iso)   	|Returns file listing automatically without sending a payload    	|
|[Minimal BD-J (Java) Devkit for PS3.zip](https://github.com/mbcrump/PS4900Linux/blob/main/bd-j/isos/Minimal%20BD-J%20(Java)%20Devkit%20for%20PS3.zip)   	|Used to create compatible BD-J images (not using the exploit)   	|

Burn .ISO files with https://www.imgburn.com/

Notes:

Official bd-j repo: https://github.com/psxdev/bd-jb

This does **NOT** work with DVDs. https://twitter.com/Sameer01988388/status/1538157532220248065

Xbox Implementation - https://twitter.com/Shykelit1/status/1538413703778881537

To send payloads use https://github.com/valentinbreiz/PS4-Payload-Sender/releases/tag/1.1
