# Framed
Digital Picture frame for NFTShowroom and local images. 

> **Note**: This repository will be used for the release of framed in its exported "finished" form. The source files for the application will be stored in a seperate repo.

## Linux

### Install instructions:

Framed is distributed as a flatpak for all supported PC platforms and can be found over on http://flathub.net. Checkout their page on how to setup flatpak and flathub for your distrobution of choice.

### Prerequisites

Framed itself should run on most modern linux distrobutions with python3 installed. However, the backend service Honeycomb requires a few additional libraries to connect to Hive and NFTshowroom.

#### Debian based distros (Ubuntu,Pop!_OS,raspberry pi OS, etc.)

``` 
sudo apt install python3-pip
pip install hivepy
pip install steempy
```

#### RPM based systems or from source distros.

Depending on your package manager of choice the setup should be the same as above. If python3,pip,hivepy,steempy are installed installations should go as expected.

### Install cont.

Next you will need to get the latest version from git along with the latest version of Framed https://github.com/VagueEntertainment/Framed/releases download and extract the archive where ever you plan on storing the program. If you plan on using Curator to manage the frame you're ready to go. Simply launch the executable with the extension that matches your hardware x86_64 for most PCs  and rpi4 for the raspberry pi 4 (might work on the 3 as well.)

If you are planning to use Framed as a standalone application you will need to download the Honeycomb-redistrbutable package from here: https://github.com/VagueEntertainment/HoneyComb-redistributable/releases. Extract the archive to the Framed directory so that it overwrites the Honeycomb-redistributable folder already in the directory.
