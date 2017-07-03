Wizard
======
By @angrykoala

Small bash script to easily install/remove scripts and binaries
All scripts installed with wizard will be moved into `/usr/local/bin`
to use wizard, just execute and give the name of the script or binary to install

To setup wizard, just type `bash wizard wizard`

> You may need to use "sudo"

## How To
wizard normal use is "wizard [scripts/binaries]" to install the scripts and binaries provided as arguments

Also, wizard admits some options: "wizard [option] [files]"      
* install [files]: same as using no options
* help: show information about the use of wizard and options
* remove [files]: removes the installed files (only those in `/usr/local/bin`)
* removeall: removes all the files installed in `/usr/local/bin`
* list: list all the files installed in `/usr/local/bin`
* copy [files]: copy installed files with wizard into your actual directory


Wizard is Open Source (GPL 3.0), you can find it here:  https://github.com/angrykoala/wizard
For further documentation check the wizard wiki: https://github.com/angrykoala/wizard/wiki
