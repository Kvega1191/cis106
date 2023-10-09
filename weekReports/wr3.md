---
name: Keven Vega
semester: Fall 2023
course: cis106
---

# Week Report 3

## Summary of presentations

### Introduction to Linux
**What is an operating system?**
An operating system provides all fundamental software features of a computer

**Aside from a kernel, what other parts make an operating system?**
Applications, Graphical Desktop Environment, Daemon Shells, Hardware 

**What is a Linux distribution?**
a complete Linux system package 

**What is Ubuntu?**
Ubuntu is a Linux distribution, freely available with both community and professional support 

**Define the following terms: Open Source, Closed source, free software**
Open source: the software may be distributed for free. The source is distributed with the software
Closed source: the software is not distributed with the source code. The user is restricted form modifying the code 
free software: the software is distributed with the source code. The software can be free of charge or obtained by a fee

**What are the 4 freedoms defined by the free software foundation?**
Freedom 0: use the software for any purpose
Freedom 1: examine the source code and modify it as you see fit 
Freedom 2: redistribute the software 
Freedom 3: redistribute your modified software 

### The basics of Virtualization
**What is virtualization?**
Virtualization is defined as creating virtual versions of something 

**List 3 benefits of virtualization**

<ul>
<li>Allows running multiple OS's on one machine without dual booting</li>
<li>Allows applications to be tested before installing them on a host machine</li> 
<li>Reduces costs by decreasing the physical hardware that must be purchased for a network </li>
</ul>

**What is a hypervisor?**
Software or Hardware in charge of creating, managing, and running virtual machines

**What is virtualbox**
Virtual box is a powerful x86 and AMD64/INtel64 virtualization product for enterprise as well as home use 

### Exploring Desktop Environments
**What is a desktop environment? (Provide 3 examples)**
A desktop environment is an implementation of the desktop metaphor made of a bunch of programs running on a top of
a computer operating system, which shares a common GUI, sometimes described as a graphical shell
<ul>
<li>GNOME</li>
<li>KDE</li> 
<li>XFCE</li>
</ul>

**List 4 common elements of desktop environments**\

<ul>
<li>Desktop settings</li>
<li>Display Manager</li> 
<li>File Manager</li>
<li>Icons</li>
</ul>

**What is Ubuntu’s default desktop environments?**
The Gnome desktop environment 

**What are the official flavors of Ubuntu?**

<ul>
<li>Edubuntu</li>
<li>Kubuntu</li> 
<li>Lubuntu</li>
<li>Ubuntu Budgie</li>
<li>Ubuntu Cinnamon</li>
<li>Ubuntu Kylin</li> 
<li>Ubuntu MATE</li>
<li>Ubuntu Studio</li>
<li>Ubuntu Unity</li>
<li>Xubuntu</li>
</ul>

### What is a Shell?
**What is Bash?**
Bash is a Unix shell and command language written by Brian Fox for the 
GNU Project as a free software replacement for the Bourne shell

**How do you access the Linux CLI?**
There are two ways to access the CLI

<ul>
<li>Terminal Emulator</li>
<li>Linux Console</li> 
</ul>

**What is a console terminal?**
A console terminal is an electronic or electromechanical hardware device that 
can be used for entering data into, and transcribing data from, a computer or a 
computing system

**What is a terminal emulator?**
A terminal emulator is a program that allows you to access the Linux CLI

**Provide 3 examples of Linux commands**

<ul>
<li>Ctrl + A= go to start of the command line</li>
<li>Ctrl + E= go to the end of the command line</li> 
<li>Ctrl + K= delete from cursor tot he end of the command line</li>
</ul>

### Managing Software
**Which command is used for updating ubuntu**
sudo apt update; sudo apt upgrade -y

**Which command is used for installing software. Provide an example.**
sudo apt install firefox flameshot caffeine -y

**Which command is used for removing software. Provide an example.**
sudo apt remove firefox flameshot caffeine -y

**Which command is used for searching for software. Provide an example.**
apt search "web browser"

**Definition of the following terms:**
#####Package:
a collection of computer programs and related data that perform specific functions or tasks

#####Library:
a collection of files, programs, routines, scripts, or functions that can be referenced in the programming code

#####Repository:
a centralized digital storage that developers use to make and manage changes to an application's source code