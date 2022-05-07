# steam-deck-for-nerds
Knowledge Repository for Steam Deck modifications, setup guides and custom hacks for engineering and programming.

Warnings and Other Such Statements:
This repository contains scripts, guides, etc written by an individual with NO affiliation with Steam. This is just a repository for my ideas and projects that involve hacking the steam deck for Engineering and Programming related tasks. Use this repositoy at your own risk. The super duper handy ![https://help.steampowered.com/en/faqs/view/1B71-EDF2-EB6D-2BB3](Valve Re-Imaging Guide) can start everything fresh and new!

# I. Initial Setup Guide
1. Starting from a fresh install of SteamOS 3 you need to do a basic setup for Steam
    - Setup language, time zone and Wifi
        - Note if the Keyboard does not show up when you click a text field you can press the Steam Button (lower left side) + the X button (left button on the right side of the controller) to pull up the on screen keyboard.
    - The Steam Deck will do updates, this takes a bit. it stalled for me after downloading completed. Hitting the B button and going back to my wifi network then hitting the A button for continue it started the installation process skipping the hold up.
    - Login to your steam profile
    - Go through the tour and explore the gaming interface. The ![https://store.steampowered.com/app/1902490/Aperture_Desk_Job/](Aperture Desk Job Game) does a great "Job" of teaching you the basic controls of the Steam Deck and I highly recommend it for newbies or Portal fans!
2. When ready enter Desktop mode
    - Hold down the power button and a new menu will drop down to restart, shutdown, sleep the machine or enter desktop mode.
    - Select enter Desktop Mode
        - If you have enabled security on the gaming mode of Steam Deck (Guide Here) you will have to enter your pin before entering desktop mode. Once in desktop mode you will have to setup additionally security per your Linux OS (by default Steam OS 3 which is Arch Linux)
    - Explore the desktop interface
        - "Start" menu is located in the bottom left corner and includes all your installed Applications as well as holding the settings menu and other useful software.
        - The icon in the bottom right of the toolbar will always bring you back to the desktop.
        - You can return to gaming mode by clicking the "Return to Gaming Mode" shortcut on the desktop.
        - The file explorer (dolphin) is the third shortcut by default on the toolbar. This accesses the file structure for the entire system like windows explorer
        - The Discover Store is a host of Flatpak softwares that can be installed on Steam OS 3 without any extra work needed in most cases.
            - Flatpak software is the recommeneded way to install tools on the Steam Deck under Arch Linux. However some tools I use are not Flatpak available yet so I will also use pacman and snap to fill in the gaps when nessecary.
            - Recommened Flatpak Software for Programmers (biased for Micro Controllers, Java, C, C++ and Python)
                - Thonny IDE
                - Visual Studio Code
                - Android Studio (Not Tested by me personally yet)
                - QT Creator
                - Arduino IDE
                - Eclipse IDE for Java Developers
                - Sublime Text
                - Github Desktop
                - MarkText
                - FileZilla
                - 
            - Recommened Flatpak Software for Engineers (biased for Micro Controllers, CAD, PCBs and CNC/3D Printing)
                - Thonny IDE
                - Arduino IDE
                - Sublime Text
                - Fritzing
                - LibrePCB
                - Raspberry Pi Imager
                - OpenSCAD
                - Prusa Slicer (Testing this week on a prusa mini!)
