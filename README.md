# KeyCastr, an open-source keystroke visualizer.
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew cask install keycastr
```

# Default browser
To disable Safari from being default web browser:

Apple (Start) -> System Preferences -> Genaral -> Default web browser -> Google Chrome

# Delete bloatware
I made it on Catalina (do not know how other versions may differ). First, I need to remount root as read-write:
```
sudo mount -u -o rw /
```

Then can actually delete trash apps like this:
```
cd /System/Applications/
sudo rm -rf Chess.app FindMy.app Maps.app Messages.app Books.app TV.app Stocks.app Home.app Mail.app Podcasts.app
```

# Terminal iTerm2
https://iterm2.com/downloads.html

To activate yakuake mode, go to Preferences -> Keys -> Hotkey press Create a Dedicated Hotkey Window, then register a hotkey and press ok. Then at Window tab choose Screen -> Screen with Cursor.

To make shortcuts work as expected (such as home, end, alt+backspace etc), go to Preferences -> Keys and add Keyboard Shortcuts with Action "Send Hex Code" manually for each shortcut. Some hex codes are described here
https://stackoverflow.com/questions/6205157/iterm-2-how-to-set-keyboard-shortcuts-to-jump-to-beginning-end-of-line
TODO Make a preset file for this repository?

0x03 - sigint

# Final Cut
## Sound Effects
There are free sound effects for fcpx from apple. To download, go to Final Cut Pro -> Download Additional Content -> Final Cut Pro Supplemental Content.
