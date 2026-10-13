# Notes 3: The GNOME DE and The Bash Shell
 
## Theory Questions
 
### What is a graphical user interface (GUI)?
A GUI is a screen interface with visual elements like icons, windows, buttons, and menus that you can click and interact with using a mouse or touchscreen.
 
### What is a desktop environment?
It's the complete visual package for an operating system. It gives you things like the top bar, application menus, windows, and the background wallpaper (for example, GNOME).
 
### What is the command line interface (CLI)?
A text-based interface where you type out commands line by line and hit Enter to make the computer do things, instead of clicking around with a mouse.
 
### How do I access the command line interface (CLI)?
You can open a terminal window right from your desktop, or switch to a full-screen virtual console using keyboard shortcuts like Ctrl + Alt + F3.
 
### What is a virtual console?
A full-screen, text-only login screen built directly into Linux that runs outside of the graphical desktop. You can jump between a few different ones using shortcuts like Ctrl + Alt + F1 through F6.
 
### What is a terminal emulator?
An app you run inside your desktop (like GNOME Terminal) that gives you a window to type commands into while you're still using your graphical desktop.
 
### What is bash?
Bash is the standard command-line shell (interpreter) used in most Linux distros. It's the program that actually reads what you type and runs it on the system.
 
### What is the shell prompt?
The little chunk of text at the start of your command line (like your username and directory ending in $) that lets you know the computer is ready for your next command.
 
---
 
## Command Definitions and Usage
 
### clear
* Definition: Empties out the current terminal screen so you have a clean workspace.
* Usage: clear
* Example: clear
 
### echo
* Definition: Prints out whatever text or string you type after it.
* Usage: echo [text]
* Example: echo "Hello CIS 106"
 
### date
* Definition: Shows the current date and time set on your system.
* Usage: date
* Example: date
 
### free
* Definition: Shows how much RAM and swap memory your system is currently using and how much is left over.
* Usage: free -h
* Example: free -h
 
### uname
* Definition: Displays basic info about your Linux system and kernel version.
* Usage: uname -a
* Example: uname -a
 
### history
* Definition: Shows a list of the previous commands you typed in your current terminal session.
* Usage: history
* Example: history | tail -n 10
 
### man
* Definition: Opens up the official instruction manual for any command.
* Usage: man [command]
* Example: man ls
 
### tldr
* Definition: Gives a quick, easy summary of how a command works with short examples instead of a long manual.
* Usage: tldr [command]
* Example: tldr tar
 
### cheat
* Definition: Displays quick cheat sheets and practical options for Linux commands.
* Usage: cheat [command]
* Example: cheat grep
 
### hostname
* Definition: Displays the name assigned to your computer on the network.
* Usage: hostname
* Example: hostname
 
### df
* Definition: Shows how much disk space is used and available on your hard drive partitions.
* Usage: df -h
* Example: df -h
 
### du
* Definition: Checks how much storage space a specific file or folder is taking up.
* Usage: du -sh [directory]
* Example: du -sh ~
 
### figlet
* Definition: Turns normal text into large, banner-style text made of ASCII characters.
* Usage: figlet [text]
* Example: figlet "Linux"