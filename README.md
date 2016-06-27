## Install

$ npm i phonegap -g

$ phonegap create


## Build 1

  $ phonegap build windows --appx=UAP --debug -- --win

-> open ./platforms/windows/CordovaApp.sln with VisualStudio
-> find at the "Project Explorer" the package "CordovaApp.Windows10 (UniversalApp)"
-> click right and select "Als Startproject festlegen..."

Danach kann mit dem [play] Button die app auf das device installiert werden
Local Device/Windows 10 -> compile "x64"
Remote Device/Windows 10 -> compile "arm"

Debug with Visual Studio !!!


## Build 2

$ phonegap build windows

-> open ./platforms/windows/CordovaApp.sln with VisualStudio
-> navigate to "Universal Windows" App and click right -> Store -> App Packet erstellen...

-> open you "windows App Manager" (ip from device)
-> select ./platforms/windwos/AppPackages/CordovaApp.Windows10_1.0.1.0_x86_x64_arm_bundle.appxupload
-> Go and Done!
