# OnAirNetScraper

CURRENT RELEASE: 23Feb2022-0800
PURGE DATE: 24Feb2022 0609

Developed by K3CLR (Amateur Extra), for further information browse to https://www.k3clr.com

WINDOWS VERSION ONLY REQUIREMENT:
The path to the OnAirNetScraper.exe file must be specified in the users variables as show below!
You MUST be within the C:\Users\[Your Home Directory]\OnAirNetScraper\ directory before running OnAirNetScraper
Running the program from outside this directory will terminate the program with a file not found error!!!

ALL NEW PYTHON BASED NET SCRAPER for DESKTOPS:

For Fedora Linux desktop, MacOS desktop, RaspberryPi ARM64 and ARMv7l and Windows the files "OnAirNetScraperPython3Fedora35-{DATE}.tgz", "OnAirNetScraperPython3MacOS-{DATE}.tgz", "OnAirNetScraperPythonRaspberryPiArm64-{DATE}.tgz", "OnAirNetScraperPythonRaspberryPiArmv7l-{DATE}.tgz" and ""OnAirNetScraperPythonWindows10-{DATE}.tgz"" are the latest Python ports of "Net Scraper".  This version of Net Scraper has been written in Python version 3 and the PyQt5 framework for improved performance.  Additionally, the Python files have been converted to a single executable by PyInstaller.  IMPORTANT NOTE:  These executables WILL NOT operate on any smartphone or tablet device.  See the discussion below for smartphone and tablet executables.   

To download Net Scraper from GitHub simply click on the GitHub icon at https://www.k3clr.com or go directly to https://github.com/chrislrobson/OnAirNetScraper.  From there, click on the desired version, which will open a webpage for that version.  On that page, click on the "download" button.

After downloading, extract the file into your home directory (required) using the command line: "tar xvfz [FILENAME.tgz]"

This command is bundled with Linux (including Raspberry Pi OS), MacOS and Windows systems and will function as shown for all these systems.

To get help run ./OnAirNetScraper/bin/OnAirNetScraper -h otherwise to get started using Net Scraper just run without the -h option.

To further improve runtime setup prior to running, the following environment vairables.  This variables should be defined with the user's ".bashrc" or ".bash_profile" files:
IMPORTANT UPDATE: The variables list below MUST BE configured or the call sign lookup menu option will not function properly.

On Linux and MacOS systems define these varaibles in your user .bashrc or .bash_profiles files:

export $HOME=PATH TO YOUR HOME DIRECTORY ...... If it's not already defined but typically it is

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

The Flutter framework version of Net Scraper ported to Mac/Linux/Windows desktop systems is no longer supported.
 
If you're interested in On-Air Net Scraper for smartphones or tablet devices, simple search the App stores for "On-Air Net Scraper".  It is available on both the Apple and Android App stores for use on smartphones and tablet devices.
