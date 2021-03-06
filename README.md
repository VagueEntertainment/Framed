# Framed
Digital Picture frame for NFTShowroom and local images. 

> **Note**: This repository will be used for the release of framed in its exported "finished" form. The source files for the application will be stored in a seperate repo.

## Linux

### Install instructions:

Framed is distributed as a flatpak for all supported PC platforms and can be found over on http://flathub.net. Checkout their page on how to setup flatpak and flathub for your distro of choice. 
> **Note:** The flatpak contains all the libraries and services you will need so if possible use it before continuing through the  rest of the instructions. 

### Prerequisites

Framed itself should run on most modern linux distrobutions with python3 installed. However, the backend service Honeycomb requires a few additional libraries to connect to Hive and NFTshowroom.

#### Debian based distros (Ubuntu,Pop!_OS,raspberry pi OS, etc.)

``` 
sudo apt install python3-pip
pip3 install hivepy
pip3 install steem
pip3 install netifaces
```

#### RPM based systems or from source distros.

Depending on your package manager of choice the setup should be the same as above. If python3,pip,hivepy,steempy are installed installations should go as expected.

### Install cont.

1. Next you will need to get the latest version of Framed from git: https://github.com/VagueEntertainment/Framed/releases. 

2. Download and extract the archive where ever you plan on storing the program.

> **Note:** If you plan on using Curator to manage the frame you're ready to go. Simply launch the executable with the extension that matches your hardware x86_64 for most PCs  and rpi4 for the raspberry pi 4 (might work on the 3 as well.)

**Stand alone**
1. Download the Honeycomb-redistrbutable package from here: https://github.com/VagueEntertainment/HoneyComb-redistributable/releases.

2. Extract the contents of the Honeycomb-redistrbutable archive into the Framed/Honeycomb-redistributable directory.

3. Test the installation by issuing this command from the Framed directory (in a terminal):
```
./Honeycomb-redistributable/service/honeycomb.py
```
If there are no errors you're ready to run Framed in stand alone mode.

## Running Framed

Once you've extracted the files in their proper places you can run framed by double clicking on the aproperiate executable Framed.x86_64 for PCs and Framed.rpi4 for raspberry pi 4 (and possibly 3). You can run it from the commandline as well by typing ./Framed.x86_64 -or- ./Framed.rpi4  from the Framed directory.


