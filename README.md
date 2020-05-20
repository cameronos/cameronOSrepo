<p align="center"><img width=60% src="https://raw.githubusercontent.com/vulture001/cameronOS/master/logo.png"></p>

A C# Cosmos based Operating System developed from a compilation of multiple C# OS's (notably Aura), by Cameron Koehler (vulture001)

## Current features
CameronOS gets frequently updated, and will continue to be. Here is a list of CameronOS's functions.

* FAT32/16/12 + Virtual FileSystem.
* PCI Device Scan.
* PS2 Keyboard.
* Restart + ACPI Shutdown via SUDO.
* Basic command interpreter.
* Exception Handler.
* Console in VGA Textmode (300x240) + Extended ASCII support

Work in progress:

* Hangman - Next update 1.6.9
* Snake - 1.6.9
* Notepad (Text editor) - 1.6.9
* File System - 1.7.1

## Screenshots

<p align="center"><img width=60% src="https://raw.githubusercontent.com/vulture001/cameronOS/master/sc1.png"></p>

<p align="center"><img width=60% src="https://raw.githubusercontent.com/vulture001/cameronOS/master/sc2.png"></p>

<p align="center"><img width=60% src="https://raw.githubusercontent.com/vulture001/cameronOS/master/sc3.png"></p>

## Contributions
Want to contribute to CameronOS? Here's how:


Fork cameronOS repo
Commit & push a new feature to the forked repository
Open a pull request so I can merge your work in this repository :)

## Try CameronOS
Download VMWare [at this address](https://my.vmware.com/en/web/vmware/free#desktop_end_user_computing/vmware_workstation_player/12_0). 
Install, and then run it.

Create a virtual machine (select Other for the type), select the .ISO file downloaded on (Link soon, still in development) and continue.

Select "Store virtual disk as a single file" and select "Finish". 

The File System isn't operable without storage, so make sure to atleast put 1 or 2 gigs of space inside the VMDK.

Now you can select CameronOS and click on "Play Virtual Machine".

## How to Compile ?
First, install Cosmos and all of the required repositories, and wait until the installation is done. 

Pre-requisites :
- Latest version of VS 2019
- .NET Core SDK 2.1
- .NET Framework 2.0

Now clone [this repository](https://github.com/vulture001/cameronOS). Inside the folder CameronOS, run CameronOSNew.sln and select "build" once Visual Studio 2019 has loaded.

If you have an error like "A project with an Output type of Class Library cannot be started directly", right click on "CameronOSNew" and select "Set as startup project", now click again on "build"!
