# Storyboarder

Based on https://wonderunit.com/storyboarder/

Storyboarder is a free tool to create storyboards.

This repository describes how to run it using a Linux vm in Linux Academy

- Browse to https://linuxacademy.com/

- Login with your account (otherwise sign up first)

You will be forwarded to the Dashboard at https://app.linuxacademy.com/dashboard

## Installing Storyboarder on a virtual machine (vm) on Linux Academy

Follow this tutorial: 

https://linuxacademy.com/blog/cloud-playground/cloud-playground-for-beginners-navigating-your-first-server/

### Step 1 – Create Your First Server
To get started, click on the Cloud Playground icon in the top navigation menu.

![Playground](https://github.com/vanHeemstraDesigns/storyboarder/raw/master/LinuxAcademy_Playground.PNG)

Follow the instructions on-screen to create your first server. Please select CentOS as the distribution, otherwise, some of the commands used in this guide won’t work properly.

![New Server](https://github.com/vanHeemstraDesigns/storyboarder/blob/master/LinuxAcademy_New_Server.PNG)

Once you’ve completed the rest of the steps in the on-screen walkthrough, your server will be launching. Once the server is “READY” we can go ahead and log into it to complete the rest of this guide.

![Ready](https://github.com/vanHeemstraDesigns/storyboarder/blob/master/LinuxAcademy_Server_Storyboarder_Ready.PNG)

### Step 2 – Log into the server

Click on the server you just launched, and you will find a “Terminal” button towards the bottom. This will open an in-browser terminal for you to log into this server, so go ahead and click it. The great thing about this in-browser terminal is that it bypasses restrictions that corporate firewalls typically have, so you can learn on the job without restriction.

![Details](https://github.com/vanHeemstraDesigns/storyboarder/blob/master/LinuxAcademy_Server_Storyboarder_Details.PNG)

Once your in-browser terminal loads, it will ask you for your username and then for your password. You will find your credentials under the “Credentials” section, as pictured above.

Please keep in mind that your temporary password will be different than the one pictured above, so copy it directly from your screen.
Also note that even though you don’t see it on the screen, keystrokes are being registered when you type in your password. It’s not visible for extra security measures, because that way you can’t see the letters or the length of the password being typed. So again, don’t worry if you are typing your password and nothing appears to be happening — it’s definitely registering the keystrokes!

Once you log in, it will immediately ask you to change your password. It does this by asking you to first enter the current password (the one you just entered from the “Temp. Password.”). Only then will it ask you to enter the new password, and it will ask you to confirm a second time.

![Login Prompt](https://github.com/vanHeemstraDesigns/storyboarder/blob/master/LinuxAcademy_Server_Storyboarder_Login_Prompt.PNG)

That’s it! You’ve now created your own custom password which you will use to login and to access admin privileges on this server going forward. Don’t forget this password!

![Logged In](https://github.com/vanHeemstraDesigns/storyboarder/blob/master/LinuxAcademy_Server_Storyboarder_Logged_In.PNG)

Great, we’re now ready to type commands and play around!

### Step 3 - Download and Install Storyboarder

Storyboarder can be downloaded from either their web site at https://wonderunit.com/storyboarder/ or directly from their Github repository (e.g. https://github.com/wonderunit/storyboarder/releases/download/v1.14.0/storyboarder-setup-1.14.0.exe)

For here, browse the Github repository at https://github.com/wonderunit/storyboarder/releases/ to select the right version for the OS (here: *latest-linux.yml*)

Instead of either installing a binary file or from source, Storyboarder has a so-called AppImage. Hence, we will use this file to install Storyboarder. Follow below instructions:

#### Install using AppImage

Based on "How To Use AppImage in Linux [Complete Guide]" at https://itsfoss.com/use-appimage-linux/

There are ways to install software in Ubuntu or any other Linux distribution. Downloading .deb or .rpm files and double click on them to install software is one of the most convenient way to that.

Recently, you might have noticed that some applications are downloaded with an extension .appimage. And you may wonder what are these .appimage files.

Next shows you what is an AppImage and how to use AppImage to install applications in Linux. In addition to that, I will also tell you a few things that you should keep in mind while using AppImage.

##### A. What is AppImage

For years, we have DEB packages for Debian/Ubuntu based Linux distributions and RPM for Fedora/SUSE based Linux distributions.

While these packages provide a convenient way of installing software to their respective distribution users, it is not the most convenient for the application developer. The developers have to create multiple packages for multiple distributions. This is where AppImage comes into picture.

[AppImage](http://appimage.org/) is a universal software package format. By packaging the software in AppImage, the developer provides just one file ‘to rule them all’. End user, i.e. you, can use it in most (if not all) modern Linux distributions.

*AppImage doesn’t install software in the traditional way*

A typical Linux software will create files at various places, requiring root permission to make these changes to the system.

AppImage doesn’t do it. In fact, AppImage doesn’t really install the software. It is a compressed image with all the dependencies and libraries needed to run the desired software.
 
You execute the AppImage file, you run the software. There is no extraction, no installation. You delete the AppImage file, the software is removed (we’ll see about it later). You can compare it to .exe files in Windows that allow you to run the software without actually going through the installation procedure.

Let me list some of the features or benefits of AppImage.

*AppImage features*

- Distribution agnostic: Can run on various different Linux distributions
- No need of installing and compiling software: Just click and play
- No need of root permission: System files are not touched
- Portability: Can be run anywhere including live disks
- Apps are in read only mode
- Software are removed just by deleting the AppImage file
- Applications packaged in AppImage are not [sandboxed](https://en.wikipedia.org/wiki/Sandbox_(computer_security)) by default.

##### B. How to use AppImage in Linux






... to be continued
