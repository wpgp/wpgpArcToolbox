# wpArcToolbox
ESRI Add-in that allows users to download rasters from WorldPop FTP server.
## Installation
- The Add-in and associated Python Toolbox can be installed by double-clicking the 'WPDwnld_btn.esriaddin' file. No other files are needed for installation.

- Users who want to make use of the Python Toolbox should download the install folder and navigate to the WPdownload.pyt file inside this folder using ArcCatalog to access the Toolbox and download tool.

- This tool requires an internet connection to work, and will raise an error before launching if not connection is found.

## Issues
When clicking the Add-in button on the interface, the following error is produced in the ArcMap Python terminal:

...
TypeError: GPToolDialog() takes at most 1 argument (2 given)
...

This is a bug known to ESRI and is logged under issue no. NIM089253. This error can be ignored.





