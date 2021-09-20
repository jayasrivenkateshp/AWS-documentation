### 01-Installation

## installation of Terraform on all operating systems

![](https://i.imgur.com/qnTisEQ.jpeg)

## installation of Terraform ( windows os )

* To install Terraform on a Windows system, download the appropriate package from the Terraform web site.

* Go to https://www.terraform.io/downloads.html.
* Download the applicable package to your local system.
* Extract the package to the folder C:\Program Files (x86).
* This path is used as an example. However, you can also the Terraform executable to any other location in your local system.
* Update the path environment variable to include the folder where your Terraform executable is located.
* Go to the Control Panel.
* Click System.
* `On a Windows 10 system, click Advanced system settings.` 
* `This option might vary in different versions of Windows`.
* The Advanced tab of the System Properties window is displayed.
* Click Environment Variables near the bottom of the window.
* The Environment Variables window is displayed.
* In the System variables pane, click Path and then click Edit.
* Click New. Add the path to the folder where your Terraform executable is located.
* Click OK to save your changes and then click OK to exit the Environment Variables windows.
* Then click OK again to exit the System Properties window.

## commands:

```
   * To verify your installation and check the version, launch Windows PowerShell and enter
   * terraform -version.
   * You’ll see the Terraform version displayed in the output.
   * For example: Terraform v0.11.
   
```

### Installation of Terraform ( Mac OS )

* To install Terrafrom on Macbook,
* https://www.terraform.io/downloads.html 
* select the version you need for your operating system. 
* Once the corresponding zip file is downloaded, 
* unzip the binary to a location that is easily referenced.

* After the binary has been unzipped, 
* you can either update the $PATH variable to point to the location where the Terrafrom binary is or you can just move it to the local bin directory. 
* If you choose the later, the on MacBook;
* you will need to execute the following command:

## command:

```
   sudo mv ./terraform /usr/local/bin
   Once it has been move to /usr/local/bin,
   it can be checked by using the “which” command:
   $ terraform —version
   $ terraform —help
```




   
