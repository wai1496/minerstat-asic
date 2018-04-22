![How it works?](https://cdn.rawgit.com/coinscrow/minerstat-asic/master/docs/logo_full.svg)

# minerstat for ASIC

**minerstat for ASIC** is mining monitoring and management software for your **Antminer** and/or **Baikal** machines.

## How it works?

![How it works?](https://cdn.rawgit.com/coinscrow/minerstat-asic/master/docs/howitworks.svg)


## Download

NOTICE: This is an **Open**-**source software** that means you can always check the source code, send

[bugs & recommendations](https://github.com/coinscrow/minerstat-asic/issues) to we can improve this software.

| Linux | Windows | Mac | Raspberry PI |
|--|--|--|--|
| Download | Download | Download | Download |

continuous build - up to date with commits


##  Build (for Developers)

This is only needed if you want to compile this software from source code.

 > Install dependencies.

 > Open Powershell / Terminal

    git clone https://github.com/coinscrow/minerstat-asic/
    npm install
    npm start

### Create executable

LINUX `electron-packager . minerstat --overwrite --asar=true --platform=linux --arch=x64 --icon=asset/1024x1024.png --prune=true --out=release-builds`

WINDOWS `electron-packager . minerstat --overwrite --asar=true --platform=win32 --arch=ia32 --icon=asset/logo.ico --prune=true --out=release-builds --version-string.CompanyName=\"minerstat OÜ\" --version-string.FileDescription=\"ASIC monitor\" --version-string.ProductName=\"minerstat\"`

MAC  `electron-packager . minerstat --overwrite --platform=darwin --arch=x64 --icon=asset/logo.icns --prune=true --out=release-builds`

RASPBERRY PI `electron-packager . minerstat --overwrite --asar=true --platform=linux --arch=armv7l --icon=asset/1024x1024.png --prune=true --out=release-builds`



/*


***© minerstat OÜ*** in 2018


***Contact:*** app [ @ ] minerstat.com 


***Mail:*** Sepapaja tn 6, Lasnamäe district, Tallinn city, Harju county, 15551, Estonia

*/


