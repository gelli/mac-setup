# mac-setup

My Mac Setup step by step


## System Update
First thing you need to do, on any OS actually, is update the system! For that: **Apple Icon > App Store > Updates**

## System Preferences

- Trackpad > Tap to click
- Trackpad > More Gestures > Swipe between full-sceen apps > 4 fingers
- Trackpad > More Gestures > App Exposé > 4 fingers
- Keyboard > Key Repeat > Fast
- Keyboard > Delay Until Repeat > Short (last before full right)
- Keyboard > Text > Delete all replacements
- Keyboard > Text > Correct spelling automatically > uncheck
- Dock > Automatically hide and show the Dock > check
- Security & Privacy > Firewall > Turn On Firewall
- Date & Time > Clock > Show date
- Accessibility > Mouse & Trackpad > Trackpad Options.. > Enable Dragging (with drag lock)
- Sharing > Computer's Name > change!
- Bluethooth > Show Bluetooth in menu bar > check
- Energy Saver > Show battery status in menu bar > check

## Keychain Access
- Preferences > Show keychain status in menu bar > check


## Finder
- Preferences > General > Show Items > Connected Servers
- Preferences > Sidebar > Movies, Pictures, Home Folder > Check
- Preferences > Sidebar > Devices > This device > Check


## Install App Cleaner
Download and install AppCleaner from https://freemacsoft.net/appcleaner/

## Install Applications
- Dropbox from https://www.dropbox.com
- Adobe Acrobat Reader DC from https://get.adobe.com/de/reader/

## App Center
- Pixelmator
- Dash
- Together3
- Things
- Xcode
- The Unarchiver


### SouceTree
- Download from https://www.sourcetreeapp.com
- Login with existing Atlassian credentials to register installation

### IntelliJ Idea
- Download from http://www.jetbrains.com/idea/
- Register with existing JetBrains account

## Install Hack font
Download and install Hack font from http://sourcefoundry.org/hack/

- Preferences > Smart Delete > On
- Preferences > Updates > Check automatically

## iTerm2
- Download iTerm2 from https://www.iterm2.com
- Start > Options > Keep in Dock
- Copy config from dotfiles/iterm to ~/.iterm
- Preferences > General > Load preferences from custom folder > ~/.iterm/
- Restart

## Run git
First run will trigger Xcode command line tools being installed

    $ git config --global user.name "Your Name Here"
    $ git config --global user.email "your_email@youremail.com"

    $ git config --global credential.helper osxkeychain

## Homebrew
- Install homebrew with command from http://brew.sh
- Run brew analytics off
- Run brew doctor after installation completed

## LiquidPrompt
- Run brew install liquidprompt

## bash_profile
ln -sf dotfiles/bash_profile ~/.bash_profile

### autoenv
    $ brew install autoenv

## Atom
Download and install Atom from https://atom.io

    $ mkdir ~/.atom
    $ ln -sf dotfiles/atom/config.cson ~/.atom/config.cson

## Python
Let's install an own python to keep the system python untouched

    $ brew install python

Running `$ which python` should output `/usr/local/bin/python`.

Update pip and it's dependency distribute

    $ pip install --upgrade distribute
    $ pip install --upgrade pip

### VirtualEnv

    $ pip install virtualenv
