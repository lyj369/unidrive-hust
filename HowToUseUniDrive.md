# Getting started with UniDrive #

## Requirements ##

Windows platform, .Net 4.0 or higher...

## Setup and Authentication ##

Unpack and double click UniDrive.exe to start the application. You need to specify the sync folder location and use/create your own CCS accounts to authenticate at least **3** clouds (i.e., Dropbox, OneDrive, Google Drive, BaiduPCS and DBank from Huawei) to make UniDrive work.

![https://unidrive-hust.googlecode.com/git/img/setup.png](https://unidrive-hust.googlecode.com/git/img/setup.png)
![https://unidrive-hust.googlecode.com/git/img/auth.png](https://unidrive-hust.googlecode.com/git/img/auth.png)
![https://unidrive-hust.googlecode.com/git/img/setcomp.png](https://unidrive-hust.googlecode.com/git/img/setcomp.png)

Specifically, click the corresponding cloud icon to open a web browser to authenticate each cloud (or create new accounts). After you enter your user name and password in the CCS's website and confirm the authentication, the browser will be closed and the cloud will be marked by a √, indicating the success of authentication.

## Normal Usage ##

After the authentication you will see a loading page initializing the cloud
environment, and then the main window appears to show panels of:
  * **Your local sync folder in UniDrive and files in each cloud.**
![https://unidrive-hust.googlecode.com/git/img/files.png](https://unidrive-hust.googlecode.com/git/img/files.png)
![https://unidrive-hust.googlecode.com/git/img/files2.png](https://unidrive-hust.googlecode.com/git/img/files2.png)
  * **File upload/download operations.**
![https://unidrive-hust.googlecode.com/git/img/op.png](https://unidrive-hust.googlecode.com/git/img/op.png)
  * **Historical records.**
![https://unidrive-hust.googlecode.com/git/img/comp.png](https://unidrive-hust.googlecode.com/git/img/comp.png)
  * **Cloud accounts you own.**
![https://unidrive-hust.googlecode.com/git/img/clouds.png](https://unidrive-hust.googlecode.com/git/img/clouds.png)


You can simply put files into the local sync folders to let them automatically be synchronized just as using CCS like Dropbox.

## Setup on Other Devices ##

Once you have setup UniDrive in one device, it will be much more convenient to deploy it to other devices. You only need to authenticate one cloud, and other clouds will automatically be authenticated.

After that, files will be synchronized across your devices automatically.

## Exit ##

Close the window won't exit the application, UniDrive maintains a system tray to
continuously monitor local sync folder, right click the tray and click exit to
exit the application.

## Trace Collection and Privacy Issue ##

UniDrive collects performance traces (not user files) for academic research and software improvement. Including but not limited to metrics such as file size and data transfer speed. No data content or user credential are accessed. You can remove all your UniDrive data in the multi-cloud as well as the local cache by running Uninstall.exe.

Any problem, please contact [cstang02@gmail.com](mailto:cstang02@gmail.com)

Thank you for your patience.