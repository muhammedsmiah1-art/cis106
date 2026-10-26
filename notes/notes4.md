# Notes 4: Managing Software and Shell Scripting
 
## 1. How to Install and Remove Software Using APT
The `apt` (Advanced Package Tool) package manager is used in Debian/Ubuntu Linux distributions to install, update, and remove software.
 
* **Update package index:**
  `sudo apt update`
* **Search for a package:**
  `sudo apt search <package_name>`
* **Install a package:**
  `sudo apt install <package_name>`
  *Example:*
  ```bash
  sudo apt install htop



* **Remove a package (keeps config files):**
`sudo apt remove <package_name>`
* **Purge a package (removes package and config files):**
`sudo apt purge <package_name>`
*Example:*
```bash
sudo apt purge htop

## 2. How to Create and Run a Shell Script
A shell script is a text file containing commands executed sequentially by the shell interpreter.
 
* **Shebang line (must be at the top):**
`#!/bin/bash`
* **Command to run a script:**
`bash ~/scripts/myscript.sh`
