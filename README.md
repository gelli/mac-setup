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

## Install App Cleaner
Download and install AppCleaner from https://freemacsoft.net/appcleaner/

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

### Brew Packages
- wget
- python3

## LiquidPrompt
- Run brew install liquidprompt

## bash_profile
ln -sf dotfiles/bash_profile ~/.bash_profile

## Atom
Download Atom from https://atom.io

### python packages
- pip3 install virtualenvwrapper
