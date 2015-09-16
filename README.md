# RadonChrome
RadonChrome is a SIMBL extension for Mac OS X to redirect Chrome notifications to Notification Center. I cannot guarantee it will work for you, but I'm currently using it with Yosemite and 64-bit Chrome 40.

### Usage
SIMBL extensions naturally require a SIMBL install on your system for use. I personally recommend [EasySIMBL](https://github.com/norio-nomura/EasySIMBL).   
**NOTE (July 2, 2015)**: EasySIMBL is not currently functional on OS X 10.9.5+, 10.10.4+, and 10.11. As an alternative you can use [SIMBL 0.9.9](http://www.culater.net/software/SIMBL/SIMBL.php) and this [workaround](https://github.com/norio-nomura/EasySIMBL/issues/26#issuecomment-117028426).

Given SIMBL is installed either: 

1. Clone the repository
2. Compile the .xcodeproj
3. Restart Chrome, and give notifications a shot! (I used [this page](http://jsbin.com/ziwod/1/edit?html,js,output) to test notifications while building the extension.)

or

1. Download the binary [HERE](https://github.com/mathcolo/RadonChrome/releases/latest).
2. Unzip the download
3. Copy the bundle file to `/Library/Application Support/SIMBL/Plugins`

### License
MIT. See the included LICENSE file in the repository for more information.