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

Once the prerequisites are installed simple download the latest version supplied above or clone the repo to your local machine. The two executables available are Framed.x86_64 and Framed.rpi4. Simply launch the version that best fits your hardware. 

