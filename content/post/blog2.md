+++
author = "Sahil Sawant"
title = "Linux Terminal Applications ....  : )"
date = "2022-10-30"
description = "Linux Terminal Applications ....  : )"
tags = [
    "",
]
categories = [
    "",
]
series = ["Themes Guide"]
aliases = ["migrate-from-jekyl"]
+++

# Hello Friends,
this is **Sahil Sawant**, and today I am going to tell you some amaizing **LINUX UTILITIES** to use...

## For Newbies,
A thing I have observed a lot is that, a lot of newbies are afraid of LINUX Terminals, and avoid using them.
Actually, drastically shifting from Windows Environment is the main problem, as the newbies are not well-equiped with the DARK-TERMINALS, and prefer using GUI applications.

So, Here are my few suggestions for starting off with few of the basic applications. ......


# 1. Ranger :

<img src="https://ranger.github.io/ranger_logo.png" width="150">

Now, the first one on our list is the **RANGER** .
It is the terminal file manager with text based User Interfacefor Unix-like Systems.
This program can accompalish file management tasks with few key-strokes, and mouse input is optional.
It uses the **VIM** key-bindings. i.e. here, you can navigate using the arrow keys.
Obviously, ther are also few addons, but for a newer stage, those will not be necessary.

    The link for GITHUB page is:
            https://github.com/ranger/ranger
        
For Installing:

    _For ARCH-Linux:_
        sudo pacman -S ranger
        
    _For UBUNTU and Its' Derivatives_
        sudo apt install ranger
        
    _For SNAP-store_
        sudo snap install ranger
        
    _most common:_
        git clone https://github.com/ranger/ranger.git
        cd ranger
        sudo make install



# 2. Neofetch 

Now, we will look to all our favourite **Neofetch** and its minimal version, the **Pfetch**.
So, Neofetch is the command-line system information tool written in **BASH**.
It displays information about your operating system, software and hardware in an aesthetic and visually pleasing way. 
The information by default is displayed alongside your operating system's logo. 
You can further configure Neofetch to instead use an image, a custom ASCII file, your wallpaper or nothing at all.

    Link to Github Pages:
        https://github.com/dylanaraps/neofetch
        
For Installing:

    _For ARCH-Linux:_
        sudo pacman -S neofetch
        
    _For UBUNTU and Its' Derivatives_
        sudo apt install neofetch
        
    _For SNAP-store_
        sudo snap install neofetch
        
    _most common:_
        git clone https://github.com/dylanaraps/neofetch.git
        cd ranger
        sudo make install



# HTOP

For basics, this is most important cli tool to check our CPU load and RAM usage.
Similar to TASK-MANAGER in Windows, this app provides both -(the graphs and processes holding) on same terminal.
It is an interactive system-monitor process-viewer and process-manager. 
It is designed as an alternative to the Unix program top.
The information displayed is configurable through a graphical setup and can be sorted and filtered interactively.
Tasks related to processes (e.g. killing and renicing) can be done without entering their PIDs.

    Link to GITHUB Pages :
            https://github.com/htop-dev/htop
            
For Installing:
        In most devices, it is pre-loded.
        but,
    
    _For ARCH-Linux:_
        sudo pacman -S htop
        
    _For UBUNTU and Its' Derivatives_
        sudo apt install htop
        
    _For SNAP-store_
        sudo snap install htop
        
    _most common:_
        git clone https://github.com/htop-dev/htop.git
        ./autogen.sh && ./configure && make
        
        
        
