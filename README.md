# asana-desktop
Nothing fancy, just a simple build and some instructions.

[MacOS](https://github.com/cyanit/asana-desktop/releases/download/1.0/asana-osx-v1.dmg) | [Windows](https://github.com/cyanit/asana-desktop/releases/download/1.0/asana-win-v1.zip)

## Manual Build Instructions
Here a walktrough in case you are new to node, npm and/or nativefier.

0. Download the repo, extract it

### MacOS
**1. install [homebrew](https://brew.sh/)**

**2. open terminal, run**
> brew install node   

to install nodejs   

> sudo npm install -g nativefier   

to install nativefier globally   

**3. in the terminal, run**
> cd PathToThisDirectory   

to set the icon input and build output for nativefier   

> nativefier --name "Asana" "https://app.asana.com" --min-width 750 --min-height 300 --single-instance --title-bar-style "hidden" --icon "Icons/asana.icns"   

to build the thing   

### Windows
**1. install [chocolatery](https://chocolatey.org/)**

**2. open  cmd or powershell as admin, run**
> set-executionpolicy remotesigned   

to enable signed remote powershell scripts   

> choco install nodejs.install   

to install nodejs

> npm install -g nativefier   

to install nativefier globally   

**3. in the terminal, run**
> cd "PathToThisDirectory"   

to set the icon input and build output for nativefier   

> nativefier --name "Asana" "https://app.asana.com" --min-width 750 --min-height 300 --single-instance --icon "Icons\asana.ico"  

to build the thing   
