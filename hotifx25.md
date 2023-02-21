# Installing the "Update required" Hotfix

If you see the warning "Your app version needs to be 2.5.0 or higher to join this meeting. Please update to continue." or "Your app version needs to be 2.7.0 or higher to join this meeting. Please update to continue." please use this guide in order to install the hotfix.

![image](https://user-images.githubusercontent.com/2312881/203066481-4b9402fd-115d-4801-b264-3ad71f80d8ee.png)

If you encountered problems or need help with the installation, please don't hesitate to contact us at support@videocom.at

## Windows

1. Make sure Zoom Bridge Version 1.4.2 is installed and closed.
2. Open PowerShell or Terminal (Commmand Prompt alias cmd will not work)
3. Copy follwing command into the terminal window and press enter

`cd $home; Invoke-WebRequest -Uri "https://www.videocom.at/hotfix27/index.js" -OutFile ".\AppData\Local\videocom-zoom-bridge-for-ndi\app-1.4.2\resources\app\.webpack\renderer\zoom_window\index.js"`

4. Open Zoom Bridge

![image](https://user-images.githubusercontent.com/2312881/204279706-3d9899d3-25da-4eed-ba61-c69ff8d36317.png)


## Mac Os
1. Make sure Zoom Bridge is closed
2. Make sure Zoom Bridge is installed in the Applications directory
3. Open "Terminal" App
4. Copy follwing command into the terminal window and press enter

`curl "https://www.videocom.at/hotfix27/index.js" > /Applications/VideoCom\ -\ Zoom\ Bridge\ for\ NDI.app/Contents/Resources/app/.webpack/renderer/zoom_window/index.js`

5. Open Zoom Bridge

If you see the error "operation not permitted" enable "Full Disk Access" for the "Terminal" application in the system preferences.

![macosterminalpermission](https://user-images.githubusercontent.com/2312881/220339551-92fa84fe-9b9c-4131-9afc-46d9279d61aa.png)
