---
layout: page
title: Getting Started
---

**Attn 2021-11-13: vibeOS is a deprecated project and this document has not been updated to reflect the current state of the project.**

This document will include instructions for both **vibeOS** and **vibeOS Legacy**, as their setup instructions are different. For most purposes, you can ignore the vibeOS Legacy instructions as it is deprecated and no longer supported.

* [Setting up vibeOS on Windows](#Windows)
* [Setting up vibeOS on macOS](#macOS)
* Setting up vibeOS on Linux
    * [Debian](#Debian)
    * [Ubuntu](#Ubuntu)
    * [Arch](#Arch)

## vibeOS Setup

Tools Required:
* A Computer
    * Windows 8, 8.1 or 10 64-Bit (Windows 7 may work but is NOT supported by vibeOS, Node.JS or Microsoft.)
    * macOS 10.13 High Sierra, 10.14 Mojave, 10.15 Catalina or 11 Big Sur (Earlier Versions may work but are not supported by vibeOS.)
    * Linux Distros: Debian, Ubuntu & Arch (Minimum Linux 4.0, Recommended Linux 5.0+)
* An Internet Connection
* Administrator permissions and/or the ability to install applications
* Comfortability using a Command Line Interface

<h2 id="Windows">Windows Setup</h2>

To get started with building vibeOS on Windows, we will need download and install NodeJS and GIT.

1. Go to the [NodeJS Website](https://nodejs.org) and download the Latest Build.
    1. Open the `.MSI` file, you will get a UAC prompt.
    2. Go through the installer, using the default options.
2. Go to the [GIT Website](https://git-scm.com/) and click "Download X.X.X for Windows".
    1. Open the `.EXE` file, you will get a UAC prompt.
    2. Go through the installer, using mostly the default options.
        * **Important: You will likely need to tailor your install to the programs installed on your PC. Take your time and ensure that your selections are correct. If you need help, reach out.**

Next up, we are going to clone the repository, install our Node modules and start the build!
For Windows, we will be using PowerShell. 

ℹ It is recommended to install PowerShell 7 if you haven't already. You can download it from the [PowerShell Repository](https://github.com/PowerShell/PowerShell/releases).

1. Open up PowerShell: You can do this by opening Start and typing PowerShell. If you have PS7 installed, open that instead.
2. Change to the directory where you want to hold your vibeOS Working Folder.
3. Make your vibeOS Working Folder and move into it.
    * `mkdir vibeOS`
    * `cd vibeOS`
4. Use GIT to clone the repository and move into it.
    * `git clone https://github.com/vibeOS/vibeos-source`
    * `cd vibeos-source`
5. Install Node Modules using NPM.
    * `npm install`
    * Ignore Deprecation Warnings
6. Build!
    * `node build`
    * Wait for the message `build finished, output found at DIR`
7. Open the `dist.html` file in your Web Browser.
    * ℹ The build script will tell you where it put the file.