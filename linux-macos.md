# PREPARE YOUR LINUX/OSX BOX FOR IONIC DEVELOPMENT

This short guide will help you to prepare your Windows machine for Ionic development. In addition to this a set of very useful tools that boost your productivity will be suggested for installation.
### THE BASICS
#### Git
As a prerequisite for the setup of all the tools that will be installed later on, you will need to install Git in order to download any necessary libraries etc. To install Git run the command:

* sudo apt-get install git

Test: 
```
git --version
```

#### NODEJS
To install the Node.js platform download and execute the installer which is provided in the official web page

* https://nodejs.org/

Test: 
```
node -v
```

#### GRUNT THE JAVASCRIPT TASK RUNNER
Grunt is a very popular automation tool. Most of the AngularJS projects out there are based on a Grunt friendly structure. Grunt starts the NodeJS server, is monitoring the filesystem for changes, and undertakes a variety set of common tasks.
Install the Grunt CLI tools by following the instruction provided in the "Getting started" web page.

* http://gruntjs.com/getting-started

Test: 
```
grunt --version
```

#### BOWER A PACKAGE MANAGER FOR THE WEB
Bower works by fetching and installing packages from all over, taking care of hunting, finding, downloading, and saving the stuff you’re looking for. Bower keeps track of these packages in a manifest file, bower.json. How you use packages is up to you. Bower provides hooks to facilitate using packages in your tools and workflows.
Install the Bower package manager by following the instructions provided in the official bower.io web page.

* http://bower.io/

Test: 
```
bower -v
```

#### PHONEGAP AND IONIC

PhoneGap and Ionic should be installed in your computer. Install the bye following the instructions in the “Install PhoneGap” and “Getting Started with Ionic” sections in the official PhoneGap and Ionic sites respectively.
http://phonegap.com/install/

* http://ionicframework.com/getting-started/

Test: 
```
ionic -v
```

### SASS SUPPORT
SASS is a technology widely used in the AngularJS applications. When it comes to PhoneGap and Ionic grunt-contrib-sass plugin is required in the most of the Ionic application you will be asked to develop. Usually this plugin is marked as required in the configuration files of the Ionic applications and Grunt will try to install it in your system and makes use of it. In order for this plugin to be able to be installed and used, Ruby and SASS should be already installed in your dev box.

#### RUBY OSX
The easiest way to Install Ruby on OSX is by using the Homebrew package manager, a process which is described in details in the following link:

* https://www.ruby-lang.org/en/documentation/installation/#homebrew

#### RUBY LINUX
The easiest way to Install Ruby on OSX is by using a package manager. Instructions for each distribution are provided in the following link:

* https://www.ruby-lang.org/en/documentation/installation/#package-managem

Test: 
```
ruby -v
```

#### SASS OSX
With Ruby installed, open a terminal and execute "gem install sass". If you get an error message then it's likely you will need to use the "sudo gem install sass"
* http://sass-lang.com/install

#### SASS LINUX
With Ruby installed, open a terminal and execute: sudo su -c "gem install sass".
* http://sass-lang.com/install

Test: 
```
sass -v
```
