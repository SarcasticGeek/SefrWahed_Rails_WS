# 1st Session #
## Agenda ##
1. Linux Setup
2. some tips in Linux Terminal
3. Setup Ruby on Linux
4. Setup Ruby on Windows
5. What's Ruby gems
6. Setup Sublime Editor
7. Intro to Ruby Language 
8. Intro to OOP with Ruby

----------

## Linux Setup ##
- download [Universal USB Installer](www.pendrivelinux.com/universal-usb-installer-easy-as-1-2-3/ "Universal USB Installer")
- download [Ubuntu 14.04](http://www.ubuntu.com/download/desktop/contribute/?version=14.04.2&architecture=amd64 "Ubuntu 14.04")
- Bring USB Flash Memory driver (greater than 4GB)
-Open Universal USB Installer ,then choose Ubuntu on Linux Distribution ,then select ubuntu iso file ,then choose your USB flash memory with formatting selected ,then choose max to create virtual memory to OS (8GB recommended) ,then click to Select button and wait to be done
-restart your computer and boot your flash memory ,then choose get Ubuntu without installing 
## some tips in Linux Terminal ##
-tips

## Setup Ruby on Linux ##
- open Terminal ,copy and paste to install Ruby with some dependencies for it.

```
sudo apt-get update
sudo apt-get install git-core curl zlib1g-dev build essential libssl-dev libreadline-dev libyaml-dev libsqlite3-dev sqlite3 libxml2-dev libxslt1-dev libcurl4-openssl-dev python-software-properties libffi-dev ruby-full
```
- Install nodejs

```
sudo add-apt-repository ppa:chris-lea/node.js
sudo apt-get update
sudo apt-get install nodejs
```

## Setup Ruby on Windows ##
- download [Ruby 2 Installer](http://dl.bintray.com/oneclick/rubyinstaller/rubyinstaller-2.0.0-p643-x64.exe "Ruby 2 Installer")
- download [Devkit for ruby 2](http://dl.bintray.com/oneclick/rubyinstaller/DevKit-mingw64-64-4.7.2-20130224-1432-sfx.exe "Devkit")
- open Ruby Installer ,while installing check those ![](C:\Users\user\Desktop\snapshot1.jpg)
- open cmd as Admin 
- write
>

	 ruby -v
- Check that wiki to install Devkit [https://github.com/oneclick/rubyinstaller/wiki/development-kit#3-extract-files](https://github.com/oneclick/rubyinstaller/wiki/development-kit#3-extract-files)
## What's Ruby gems ##
Library packaging and distribution for Ruby. 
- Upgrade it [https://rubygems.org/pages/download](https://rubygems.org/pages/download)

- Install Rails gem
>

	sudo gem install rails --no-ri --no-rdoc
- Write in Terminal 
>
 
    rails -v 


