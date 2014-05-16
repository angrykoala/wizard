wizard
======
Programmed by Demiurgos

Small bash script to easily "install"/remove scripts and binaries
All scripts installed with wizard will be moved into /usr/local/bin
to use wizard, just execute and give the name of the script or binary to install

To setup wizard, just type bash wizard wizard (this will "autoinstall" wizard)

MANUAL:
wizard normal use is "wizard [scripts/binaries]" to install the scripts and binaries provided as arguments

also, wizard admits some options: "wizard [option] [files]
-install [files]: same as using no options
-help: show information about the use of wizard and options
-remove [files]: removes the installed files (only those in /usr/local/bin)
-removeall: removes all the files installed in /usr/local/bin
-list: list all the files installed in /usr/local/bin
-copy [files]: copy installed files with wizard into your actual directory


gfxwizard(beta) allows an installation with wizard using a zenity graphical interface (only installation), to use this, you will need to have non graphic wizard installed and zenity
