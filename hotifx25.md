# Installing the "Update required" Hotfix

## Windows

1. Make sure Zoom Bridge is closed
2. Open PowerShell or Terminal 
3. Copy follwing command into the Terminal window and press enter
`Invoke-WebRequest -Uri "https://www.videocom.at/hotfix/index.js" -OutFile ".\AppData\Local\videocom-zoom-bridge-for-ndi\app-1.4.2\resources\app\.webpack\renderer\zoom_window\index.js"`
4. Open Zoom Bridge


## Mac Os
1. Make sure Zoom Bridge is closed
2. Make sure Zoom Bridge is installed in the Applications directory
3. Open "Terminal" App
4. Copy follwing command into the Terminal window and press enter
`curl "https://www.videocom.at/hotfix/index.js" > /Applications/VideoCom\ -\ Zoom\ Bridge\ for\ NDI.app/Contents/Resources/app/.webpack/renderer/zoom_window/index.js`
5. Open Zoom Bridge
    
