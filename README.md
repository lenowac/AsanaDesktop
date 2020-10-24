# asana-desktop
Nothing fancy, just a simple build script.

I wish I could just upload the builds here, but they are too big for GitHub.

## Manual Build Instructions
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
