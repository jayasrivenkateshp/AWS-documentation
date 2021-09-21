### installation of Session manager

## inatallation of session manager for all Operating systems

```
   Windows
   Mac OS
   Linux
```

### installation of session manager in windows

Install the Session Manager plugin on Windows
Download the installer using the following URL.

https://s3.amazonaws.com/session-manager-downloads/plugin/latest/windows/SessionManagerPluginSetup.exe
Run the downloaded installer, and follow the on-screen instructions.

Leave the install location box blank to install the plugin to the default directory.
C:\%PROGRAMFILES%\Amazon\SessionManagerPlugin\bin\

Verify that the installation was successful. For information, see Verify the Session Manager plugin installation.

### Install the Session Manager on macOS

You can install the Session Manager plugin on macOS using the bundled installer.

Important
The bundled installer doesn't support installing to paths that contain spaces.

To install the Session Manager plugin using the bundled installer (macOS)

Download the bundled installer.

curl "https://s3.amazonaws.com/session-manager-downloads/plugin/latest/mac/sessionmanager-bundle.zip" -o "sessionmanager-bundle.zip"
Unzip the package.

unzip sessionmanager-bundle.zip
Run the install command.

### Install Session Manager on Linux

Download the Session Manager plugin RPM package.
Intel 64-bit (x86_64
curl "https://s3.amazonaws.com/session-manager-downloads/plugin/latest/linux_64bit/session-manager-plugin.rpm" -o "session-manager-plugin.rpm"
Intel 32-bit (x86)
curl "https://s3.amazonaws.com/session-manager-downloads/plugin/latest/linux_32bit/session-manager-plugin.rpm" -o "session-manager-plugin.rpm"
ARM 64-bit (arm64)
curl "https://s3.amazonaws.com/session-manager-downloads/plugin/latest/linux_arm64/session-manager-plugin.rpm" -o "session-manager-plugin.rpm"
Run the install command.
sudo yum install -y session-manager-plugin.rpm
Verify that the installation was successful. For information, see Verify the Session Manager plugin installation.



