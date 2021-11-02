# CPP_Windows_Dependencies

## Installing MINGW

run the mingw-w64-install.exe file in your computer an installation wizard will pop up in the screen.

	Assure the thread option is selected as posix.
	Assure the architecture option is selected as x86_64
	Click next and select the folder where you want to install.
	Click next and the wizard will install the MINGW cmpiler. 

### Add MINGW path to environmental variables

	If the path was not changed during installation, MINGW was probbly installed in the folder C:\Program Files\mingw-w64
	Add the following path to the environmental variables under system and path: C:\Program Files\mingw-w64\x86_64-8.1.0-posix-seh-rt_v6-rev0\mingw64\bin
	To access the environmental variables in windows go to "This PC" right click on the empty space of the window and select "Properties". On the left click on "Advanced Settings". At the bottom click on "Environmental Variables".
	
## References

	https://www.youtube.com/watch?v=03DAsDRmtvA