HexRat is currently a prototype and is provided AS IS. It may also change, suffer feature creep, or never be updated again with no warning

It worked on my end (under both windows and Linux, though some features are disabled on Linux. mostly VA related so you won't miss them) and I consider it generally safe for ratting but YOU are solely responsible if you use this and it accidentally or erronously goofs up, or if you miss something important because it was filtered

It should not throw errors at you anymore, if it does please let me know

Known issue: it will throw errors if it's left running while the desktop is locked, because it won't be able to reach the clipboard

When it's cutting Mecha or Quit-messages short, it's set for the exact font and window size I'm using, results may vary

# Installation

1. You will need Python and the modules: "pyperclip" and "pygame"

2. Open hexrat.py and change the soundfile names to the ones you want to use and put them in hexchat/sounds 

3. put hexrat.py and hexrat-loader.py in Hexchat/addons and it will auto-start.


Recommended: use a dark color scheme or you are going to have a bad time with the colors I set. You can use the provided colors.conf

If it crashes or you just want to reload it faster, type /hr

If you want to use it for console or Ody you will have to change the sound trigger conditions, I set them to use ssk (skip)
