De Nora Tech CISEP Logger Install Instructions

1. Download the sharepoint folder provided to DNT IT from MJM Automation
2. Extract the .zip folder, making sure the folder contains two subfolders: DNT_CISEP_v1.0 and Installer
3. DNT_CISEP_v1.0 will contain the executable application, no need to do anything with this, other than having it in the downloads folder with the installer
4. Open the installer folder, and run the "install.exe" application
5. Set the install path for the file to be C:\De Nora Tech Lab Logger
	If this folder is not already created, create it
6. Leave the path for the National Instrument library as C:\National Instruments
7. Run the installer
8. You will be prompted to restart the computer after completion
9. Configure the Device configuration for the NI equipment
10. The device should be named 
	see screenshot in the folder for correct conventions of chassis and modules
11. Move the files in located in the Sharepoint drive into the C:\ProgramData folder. While in this folder, also create an "ErrorLog" folder. This is where any errors will get dumped.
12. Copy the "Pump Calibration Files" folder into the C:\De Nora Tech Lab Logger directory
12. Open the application and make sure that it loads properly