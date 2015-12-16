# RadonChrome
RadonChrome is a SIMBL extension for Mac OS X to redirect Chrome notifications to Notification Center. I cannot guarantee it will work for you, but I'm currently using it with Yosemite and 64-bit Chrome 40.

![preview](preview.png)

### Notice (December 15, 2015)
In OS X El Capitan, disabling System Integrity Protection is required to install SIMBL. I'm hesitant to continue updating RadonChrome when SIP mods are required. I'm investigating other ways to accomplish RadonChrome's task without playing with SIP, including maintaining a Chromium fork with direct to system notifications built-in. If this is something you're interested in helping with, please let me know!

### Usage
SIMBL extensions naturally require a SIMBL install on your system for use. I personally recommend [EasySIMBL](https://github.com/norio-nomura/EasySIMBL) for OS X Yosemite and below. On OS X El Capitan, SIMBL must be installed with SIP turned off, as explained [here](https://github.com/norio-nomura/EasySIMBL/issues/26#issuecomment-117028426). 

Given SIMBL is installed either: 

1. Clone the repository
2. Compile the .xcodeproj
3. Restart Chrome, and give notifications a shot! (I used [this page](http://jsbin.com/ziwod/1/edit?html,js,output) to test notifications while building the extension.)

or

1. Download the binary [HERE](https://github.com/mathcolo/RadonChrome/releases/latest).
2. Unzip the download
3. Copy the bundle file to /Library/Application Support/SIMBL/Plugins
4. Restart Chrome, and give notifications a shot!

### License
MIT. See the included LICENSE file in the repository for more information.
