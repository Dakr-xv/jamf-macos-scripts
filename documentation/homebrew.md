Jamf Pro Scripts for macOS Management - Homebrew
==============
This script runs during the post-DEP SplashBuddy run and installs [Homebrew](https://brew.sh) for the initially created user

Requirements
------------
1. DEP: Yes 
2. [SplashBuddy](https://github.com/Shufflepuck/SplashBuddy): Yes

macOS Compatibility Matrix
------------
This script has been tested on the following macOS versions

| Tested macOS Major Version               | Tested Minor Versions                          | Expected Working Minor Versions     | DEP Required |
|----------------------------------------- |------------------------------------------------|-------------------------------------|--------------|
| High Sierra                              | 10.13.4                                        | 10.13.0-10.13.4                     | Yes          |

Script Operations
------------
This script will perform the following operations

1. Check for and install XCode Command-line Tools
2. Chefk for and install Homebrew for the initially created user

Limitations
------------

1. This script requires access to Apple for XCode Command-line Tools installation
2. This script requires access to brew.sh and github.com for Homebrew installation
3. This script requires an initial user to be created by the end user during the macOS OOBE 

Known Issues
------------
1. None so far :)

Use Cases
------------
Getting Homebrew setup for the end user or for automated brew package installations in later scripts

[Back to main README](../README.md)