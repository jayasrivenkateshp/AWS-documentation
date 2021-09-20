## 01-Installation
installation of `AWS CLI`

## AWS CLI is available for all Operating systems
 >` Windows`
 >` Linex`
 >` MAC OS`
 > `Docker`
 
### How to install AWS CLI ?

  # installation steps
  
* step 1 - open this URL https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html
* step 2 - click on latest version of AWS CLI
* step 3 - then select ur operating system (OS)

## windows (OS)

* `Install or update the AWS CLI version 2 on Windows using the MSI installer`(`select this~)
*  https://awscli.amazonaws.com/AWSCLIV2.msi
* install AWS CLI

## commands:

```
    $ aws --version - current version
    $ aws configure - configure `AWS CLI` for your account
    $   ls  - list your files
```
      

## linex (OS)

* `Install or update the AWS CLI version 2 on Windows using the MSI installer`(`select this)
*  https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip
* install AWS CLI


##  commands:
   
```
   curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
   unzip awscliv2.zip
   sudo ./aws/install - installation
   
   curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64-2.0.30.zip" -o "awscliv2.zip"
   unzip awscliv2.zip
   sudo ./aws/install - version
```

## MAC OS

* `Install and update the AWS CLI version 2 using the macOS user interface`(select this~)
*  Install and update the AWS CLI version 2 using the macOS command line
*  https://awscli.amazonaws.com/AWSCLIV2.pkg
*  install AWS CLI

## commands

```
   $ sudo ln -s /folder/installed/aws-cli/aws /usr/local/bin/aws - installation on local folder
   $ sudo ln -s /folder/installed/aws-cli/aws_completer /usr/local/bin/aws_completer
```

## Docker

*`Run the official AWS CLI version 2 Docker image`(`select this`)
* Use specific versions and tags
* Update to the latest Docker image
* Share host files, credentials, environment variables, and configuration
* Shorten the Docker command
* inatall AWS CLI

## commands

```
    docker --version - version
    docker run --rm -it amazon/aws-cli command    
```
