# Pycord
<p align="center"><img width="80%" src="https://raw.githubusercontent.com/vulture001/cameronOS/master/logo.png"></p>
Complex C# COSMOS based Operating System developed from a compilation of multiple OS's (notably Aura)<br>

### Languages and programs used
<p>
    <A href="https://en.wikipedia.org/wiki/C# (programming language)"><img height="28" width="28" src="https://iconape.com/wp-content/png_logo_vector/c.png" /></a>
    <A href="https://www.gocosmos.org/"><img height="28" width="65" src="https://www.gocosmos.org/wp-content/uploads/2018/01/CosmosLogo.png" /></a>
</p>

### Status
<p>
    <a href="https://github.com/vulture001/robber/blob/master/client.lua"><img src="https://img.shields.io/badge/build-passing-brightgreen" alt="Build Status"></a>
    <a href="https://github.com/vulture001/cameronOS/blob/master/LICENSE"><img src="https://img.shields.io/github/license/vulture001/cameronOS" alt="License"></a>
    <img src="https://img.shields.io/github/repo-size/vulture001/cameronOS" alt="Size">
</p>

### Current features
CameronOS rarely gets updated - Here is a list of CameronOS's current functions.

- FAT32/16/12 + Virtual FileSystem.
- PCI Device Scan.
- PS2 Keyboard.
- Restart + ACPI Shutdown via SUDO.
- Basic command interpreter.
- Exception Handler.
- Console in VGA Textmode (300x240) + Extended ASCII support

### Work in progress
- Hangman - Next update 1.6.9
- Snake - 1.6.9
- Notepad (Text editor) - 1.6.9
- File System - 1.7.1

### Screenshots
<p align="center"><img width=60% src="https://raw.githubusercontent.com/vulture001/cameronOS/master/sc1.png"><br>
<img width=60% src="https://raw.githubusercontent.com/vulture001/cameronOS/master/sc2.png"><br>
<img width=60% src="https://raw.githubusercontent.com/vulture001/cameronOS/master/sc3.png"></p>

### Contributions
Want to contribute to CameronOS? Here's how:

- Fork cameronOS repo
- Commit & push a new feature to the forked repository
- Open a pull request so I can merge your work in this repository

### Try CameronOS
- Download VMWare [at this address](https://my.vmware.com/en/web/vmware/free#desktop_end_user_computing/vmware_workstation_player/12_0). 
- Create a virtual machine (select Other for the type)
- Select the .ISO file downloaded on (Link soon, still in development) and continue.
- Select "Store virtual disk as a single file" and select "Finish". (The File System isn't operable without storage, so make sure to atleast put 1 or 2 gigs of space inside the VMDK.)
- Now you can select CameronOS and click on "Play Virtual Machine".

### How to compile ?
First, install CosmosOS and all of the required repositories, and wait until the installation is done. 

Pre-requisites :
- Latest version of VS 2019
- .NET Core SDK 2.1
- .NET Framework 2.0

Now clone [this repository](https://github.com/vulture001/cameronOS). Inside the folder CameronOS, run CameronOSNew.sln and select "build" once Visual Studio 2019 has loaded.

If you have an error like "A project with an Output type of Class Library cannot be started directly", right click on "CameronOSNew" and select "Set as startup project", then click again on "Build".
