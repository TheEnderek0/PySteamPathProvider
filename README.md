# PySteamPathProvider
A library for providing steam paths and app names, given a Steam AppID (integer).

### GetSteamInstallPath()
Retrieve the installation path of Steam.
### GetInstallationDirs()
Get every directory that Steam can install games to.
### GetAppsDictionary()
Retrieve installation directories of every app the user has currently installed. **SLOW!**

### GetApp(appid)
Retrieve information only about this app in the form of a tuple (name, installpath).
Significantly faster than GetAppsDictionary().
### GetAppName(appid)
Retrieve only the name of this specific app.
### GetAppInstallPath(appid)
Retrieve only the installation path of this specific app.
