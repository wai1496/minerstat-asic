![How it works?](https://cdn.rawgit.com/coinscrow/minerstat-asic/master/docs/logo_full.svg)

# minerstat for ASIC

**minerstat for ASIC** is mining monitoring and management software for your **Antminer** and/or **Baikal** machines.

## How it works?

<img src="https://cdn.rawgit.com/coinscrow/minerstat-asic/master/docs/howitworks.svg" width="50%">

## Download

NOTICE: This is an **Open**-**source software** that means you can always check the source code, send

[bugs & recommendations](https://github.com/coinscrow/minerstat-asic/issues) to we can improve this software.

| Linux | Windows | Mac | Raspberry PI |
|--|--|--|--|
| <a href='https://ci.appveyor.com/api/projects/coinscrow/minerstat-asic/artifacts/release-builds/minerstat-asic-linux.zip'><img alt="Download" src="https://cdn.rawgit.com/coinscrow/minerstat-asic/master/docs/button_download.svg" width="95%"></a> | <a href='https://ci.appveyor.com/api/projects/coinscrow/minerstat-asic/artifacts/release-builds/minerstat-asic-windows.zip'><img alt="Download" src="https://cdn.rawgit.com/coinscrow/minerstat-asic/master/docs/button_download.svg" width="95%"></a> | <a href='https://github.com/coinscrow/minerstat-asic/releases/download/1.0/minerstat-asic-mac.zip'><img alt="Download" src="https://cdn.rawgit.com/coinscrow/minerstat-asic/master/docs/button_download.svg" width="95%"></a> | <a href='https://ci.appveyor.com/api/projects/coinscrow/minerstat-asic/artifacts/release-builds/minerstat-asic-raspberry.zip'><img alt="Download" src="https://cdn.rawgit.com/coinscrow/minerstat-asic/master/docs/button_download.svg" width="95%"></a> |

continuous build - up to date with commits


##  Build (for Developers) <img alt="Status" src="https://ci.appveyor.com/api/projects/status/github/coinscrow/minerstat-asic?branch=master&svg=true" alt="Build">

This is only needed if you want to compile this software from source code.

 > Install dependencies.

 > Open Powershell / Terminal
    
    npm install -g node-gyp
    npm install -g electron-packager
    git clone https://github.com/coinscrow/minerstat-asic/
    npm install
    npm start

### Create executable

LINUX `npm run-script package-linux`

WINDOWS `npm run-script package-win`

MAC  `npm run-script package-mac`

RASPBERRY PI `npm run-script package-pi`



/*


***© minerstat OÜ*** in 2018


***Contact:*** app [ @ ] minerstat.com 


***Mail:*** Sepapaja tn 6, Lasnamäe district, Tallinn city, Harju county, 15551, Estonia

*/


