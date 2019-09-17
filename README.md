Keyboard shortcuts
Tab manipulation
Ctrl + ` : Global Summon from taskbar
Win + Alt + p : Preferences (Or right click on title bar)
Ctrl + t : New tab dialog (maybe you want to open cmd as admin?)
Ctrl + w : Close tab
Shift + Alt + number : Fast new tab:
1. CMD
2. PowerShell
Alt + Enter : Fullscreen
Shell
Ctrl + Alt + u : Traverse up in directory structure (lovely feature!)
End, Home, Ctrl : Traverse text as usual on Windows
Ctrl + r : History search
Shift + mouse : Select and copy text from buffer
Right click / Ctrl + Shift + v : Paste text

Aliases
There is simple support for aliases. They can be created by using the alias command like this: alias ls=ls --color $*. They are pretty much just doskeys in /config/aliases. One per line. And make sure to handle arguments by putting argument variables $* somewhere.

Updating + Building
There is not much going on here. But if you want to get most recent updates for Conemu just tick auto-updating in preferences. If you want to clone the repo and build it yourself, you will need PowerShell >=3.0 and 7z. When you are set on that, just run scripts/build.ps1.

Documentations
Most of the Cmder functionality are documented in the readme file on GitHub. We have extented help available in Cmder Wiki, also regarding integration.

If you're having trouble with anything, please have a look at the GitHub issues, or create a new one.
We'll be happy to help, but you might have a better chance to find solutions on the pages of the upstream projects. Those are:

Console emulator ~ Conemu
Cmd.exe enhancements ~ clink
Unix tools on windows ~ git for windows
