# OnAirNetScraper

Developed by K3CLR (Amateur Extra), for further information browse to https://www.k3clr.com

ALL NEW PYTHON BASED NET SCRAPER for DESKTOPS:

For Fedora Linux desktop, MacOS desktop, RaspberryPi ARM64 and ARMv7l and Windows the files "OnAirNetScraperPython3Fedora35-{DATE}.tgz", "OnAirNetScraperPython3MacOS-{DATE}.tgz", "OnAirNetScraperPythonRaspberryPiArm64-{DATE}.tgz", "OnAirNetScraperPythonRaspberryPiArmv7l-{DATE}.tgz" and ""OnAirNetScraperPythonWindows10-{DATE}.tgz"" are the latest Python ports of "Net Scraper".  This version of Net Scraper has been written in Python version 3 and the PyQt5 framework for improved performance.  Additionally, the Python files have been converted to a single executable by PyInstaller.  IMPORTANT NOTE:  These executables WILL NOT operate on any smartphone or tablet device.  See the discussion below for smartphone and tablet executables.   

To download Net Scraper from GitHub simply click on the GitHub icon at https://www.k3clr.com or got directly to https://github.com/chrislrobson/OnAirNetScraper.  From there, click on the desired version, which will open a webpage for that version.  On that page, click on the "download" button.

After downloading, extract the file into your home directory (required) using the command line: "tar xvfz [FILENAME.tgz]"

This command is bundled with Linux (including Raspberry Pi OS), MacOS and Windows systems and will function as shown for all these systems.

To get help run ./OnAirNetScraper/bin/OnAirNetScraper -h otherwise to get started using Net Scraper just run without the -h option.

To further improve runtime setup prior to running the following environment vairables which should be defined with the user's ".bashrc" or ".bash_profile" files:
IMPORTANT UPDATE: The variables list below MUST BE configured or the call sign lookup menu option will not function properly.

On Linux and MacOS systems define these varaibles in your user .bashrc or .bash_profiles files:

export $HOME=PATH TO YOUR HOME DIRECTORY ...... If its not already defined but typically it is

export OAS_CALLSIGN="YOUR CALL SIGN"

export OAS_FIRSTNAME="FIRST NAME"

export OAS_LASTNAME="LAST NAME"

export OAS_STATUS="Station Operator"

export OAS_NOTES="TBD"

export QRZ_USER="YOUR CALL SIGN"

export QRZ_PASSWORD="YOUR QRZ.COM PASSWORD"

Open the classic Control Panel.
Navigate to Control Panel\User Accounts\User Accounts.
On the left, click on the Change my environment variables link.

On Windows run the "Edit the system environment variables" GUI and follow these steps.  
1. Open the classic Control Panel.
2. Navigate to Control Panel\User Accounts\User Accounts.
3. On the left, click on the Change my environment variables link.
4.  Select the "Environment Variables" button
5.  Under the "User variables for USERNAME" select the "New" button
6.  Create a new variable for:  OAS_CALLSIGN, OAS_FIRSTNAME, OAS_LASTNAME, OAS_STATUS, QRZ_USER, and QRZ_PASSWORD as show for the UNIX systems above.

or from the command prompt:
1. Open a new command prompt
2. Type the following command: setx <variable_name> "<variable_value>"
3. Substitute <variable_name> with the actual name of the variable you want to create.
4. Substitute "<variable_value>" with the value you want to assign to your variable.

If you do not have a QRZ.COM subscription account, the above configuration is not required.  However, Net Scraper uses QRZ.COM for call sign lookup, therefore, this feature will not function.

FLUTTER BUILT SMARTPHONE, TABLET and LINUX SYSTEMS:

To use the smartphone, Flutter based version of Net Scraper, read explanation that follows, however, the above Python version is the recommended version to use on desktop computers

A Linux port of "On-Air Net Scraper".  On-Air Net Scraper is a Flutter App which extracts Netlogger server data.  Typically, this app is of interest to Amateur Radio operators who follow Amateur Radio Net sessions.

[DEPRECATED NO LONGER SUPPORTED]There are two(2) archive files presented here.  File "OnAirNetScraperV3.0.0-39-Fedora35-Linux.tgz" is for deployment on desktop Linux OS.  File "OnAirNetScraper-ARM64-RaspberryPi-13Noov2021.tgz" is a Raspberry Pi Arm64 RaspiOS distribution.

[DEPRECATED NO LONGER SUPPORTED]The Raspberry Pi distribution will ONLY run on Arm64 OS and NOT Arm32 OS.  

[DEPRECATED NO LONGER SUPPORTED]While file OnAirNetScraperV3.0.0-39-Fedora35-Linux.tgz was built on a Fedora 35 Linux distribution it may work on any Linux distribution.

[DEPRECATED NO LONGER SUPPORTED]Simply untar the file, set a path to the untarred file path and execute the file "onairnetscraper"

[DEPRECATED NO LONGER SUPPORTED]What works: most everything.

[DEPRECATED NO LONGER SUPPORTED]What DOES NOT work:  This App is originally built for iPhone and Android devices which incorperates a feature call "WebView".  WebView provides hooks into a smartphone browser App for browsing the Internet.  However, WebView has NOT been ported to desktop systems as of yet so none of these features in this Linux OnAir Net Scraper will function and will instead display an error stating this fact. 
 
If your interested in On-Air Net Scraper for smartphones or tablet devices, simple search the App stores for "On-Air Net Scraper".  It is available on both the Apple and Android App stores.
