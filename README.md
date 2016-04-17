ssms-wakatime
=====================

WakaTime is a productivity & time tracking tool for programmers. Once the WakaTime plugin is installed, you get a dashboard with reports about your programming by time, language, project, and branch.


Installation
------------

1. Download WakaTime.dll and Nlog.config

2. Inside regedit.exe go to -> `HKEY_CURRENT_USER\Software\Microsoft\SQL Server Management Studio\11.0_Config\AutomationOptions\LookInFolders`

3. Copy WakaTime.Addin to one of those folders (I recommend you to copy into `C:\ProgramData\Application Data\Microsoft\MSEnvShared\Addins`)

4. Edit WakaTime.Addin and change the node Extensibility/Addin/Assembly to the full path of WakaTime.dll you downloaded

5. Enter your [api key](https://wakatime.com/settings#apikey), then press `enter`.

6. Use SQL Server Management Studio like you normally do and your time will be tracked for you automatically.

7. Visit https://wakatime.com to see your logged time.


Screen Shots
------------

![Project Overview](https://wakatime.com/static/img/ScreenShots/ScreenShot-2014-10-29.png)

Contributing
------------
**TO DO**

1. Implement logging
