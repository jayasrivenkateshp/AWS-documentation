### Installation of GIT

![](https://i.imgur.com/myVdGJe.jp

### installation of GIT on all operating systems

```
   Windows OS 
   Mac OS
   Linex
```

### Download Git for Windows

* Browse to the official Git  website: https://git-scm.com/downloads
* Click the download link for Windows and allow the download to complete.
# Extract and Launch Git Installer
* Browse to the download location (or use the download shortcut in your browser). 
* Double-click the file to extract and launch the installer.
* Allow the app to make changes to your device by clicking Yes on the User Account Control dialog that opens
* Review the GNU General Public License, and when you’re ready to install, click Next.
* The installer will ask you for an installation location. Leave the default, unless you have reason to change it, and click Next.
* A component selection screen will appear. Leave the defaults unless you have a specific need to change them and click Next.
* The installer will offer to create a start menu folder. Simply click Next.
* Select a text editor you’d like to use with Git. Use the drop-down menu to select Notepad++ (or whichever text editor you prefer) and click Next.
* The next step allows you to choose a different name for your initial branch. 
* The default is 'master. Unless you're working in a team that requires a different name, leave the default option and click Next.
* This installation step allows you to change the PATH environment.
* The PATH is the default set of directories included when you run a command from the command line. Leave this on the middle (recommended) selection and click Next.
* Server Certificates, Line Endings and Terminal Emulators
* The installer now asks which SSH client you want Git to use. Git already comes with its own SSH client, so if you don't need a specific one, 
* leave the default option and click Next.
* The next option relates to server certificates. Most users should use the default.
*  If you’re working in an Active Directory environment, you may need to switch to Windows Store certificates. Click Next.
* The next selection converts line endings. It is recommended that you leave the default selection. 
* This relates to the way data is formatted and changing this option may cause problems. Click Next.
* Choose the terminal emulator you want to use. The default MinTTY is recommended, for its features. Click Next.
* The installer now asks what the git pull command should do. The default option is recommended unless you specifically need to change its behavior. 
* Click Next to continue with the installation.
* Next you should choose which credential helper to use. Git uses credential helpers to fetch or save credentials. 
* Leave the default option as it is the most stable one, and click Next.
* The default options are recommended, however this step allows you to decide which extra option you would like to enable. 
* If you use symbolic links, which are like shortcuts for the command line, tick the box. Click Next.
* Depending on the version of Git you’re installing, it may offer to install experimental features. 
* At the time this article was written, the options to include support for pseudo controls and a built-in file system monitor were offered.
* Unless you are feeling adventurous, leave them unchecked and click Install.

## Complete Git Installation Process

* Once the installation is complete, tick the boxes to view the Release Notes or Launch Git Bash, then click Finish.
 
## How to Launch Git in Windows

* Git has two modes of use – a bash scripting shell (or command line) and a graphical user interface (GUI).

## Launch Git Bash Shell
* To launch Git Bash open the Windows Start menu, type git bash and press Enter (or click the application icon).
## Launch Git GUI
* To launch Git GUI open the Windows Start menu, type git gui and press Enter (or click the application icon).

### Download GIT for Mac OS

* Download the latest Git for Mac installer.
* Follow the prompts to install Git.
* Open a terminal and verify the installation was successful by typing git --version:
* 
## commands:

```
   $ git --version - git version 2.9.2
```

# example

* Configure your Git username and email using the following commands, replacing Emma's name with your own. These details will be associated with any commits that you create:
 To make Git remember your username and password when working with HTTPS repositories, configure the git-credential-osxkeychain helper.

       
```       
    $ git config --global user.name "Emma Paris"
    $ git config --global user.email "eparis@atlassia
```    
### Install Git on Linux

* Debian / Ubuntu (apt-get)
* Git packages are available via apt:
* From your shell, install Git using apt-get:
* 
## commands:

```
   $ sudo apt-get update
   $ sudo apt-get install git
```   
* Verify the installation was successful by typing git --version:

## commands:

```
   $ git --version - git version 2.9.2
```


## example:

Configure your Git username and email using the following commands, replacing Emma's name with your own. These details will be associated with any commits that you create:

```
   $ git config --global user.name "Emma Paris"
   $ git config --global user.email "eparis@atlassian.com"
```
   























