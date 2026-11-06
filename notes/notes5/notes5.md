# notes 5
 
## 1. commands
 
    ls
    ```
  * tto see everything, including hidden files
    ```bash
    ls -a
    ```
### `ls`
**definition:** this command lists all the files and folders that are in your  directory
**formula:** `ls [options] [path]`
**examples:**
* and to see what's in the folder:

    ```bash
 
### `pwd`
* **definition:** stands for print working directory. It shows you the full path of where you are right now in the terminal
* **formula:** `pwd`
* **examples:**
  * to check your current location:

    ```bash
    pwd
    ```
 
### `cd`
* **definition:** stands for change directory and you use this to move around from folder to folder
* **formula:** `cd [directory-name]`
* **examples:**
  * to jump back to your home folder:
    ```bash
    cd ~
    ```
  * to go back up one folder level:
    ```bash
    cd ..
    ```
 
---
 
## 2. questions
 
### 1. What is a variable?
a  variable is basically a container that holds a value or bit of data in the system  which you can use and change later in a script or command
 
### 2. How do I use a variable?
you set it by giving it a name and a value (like `name=value`), and whenever you want to use what's inside it, you put a dollar sign in front of it (like `$name`).
 
### 3. What is an environment variable?
it's a system wide variable that stores settings or info that the operating system and running programs use
 
### 4. What is a user defined variable?
a variable that you (the user) create yourself in the terminal or a script for whatever specific thing you're working on.
 
### 5. What is the root directory?
it is the absolute highest starting point of the entire Linux file system, represented just by a single slash (`/`).
 
### 6. What does “Parent Directory” mean?
it's the folder that sits one level directly above the folder you are currently inside. You point to it using `..`.
 
### 7. What does “Current working directory” mean?
it's simply the folder that your terminal window is currently focused on and working inside right now.
 
### 8. What is an absolute path? Include an example
an absolute path is the full or  exact address of a file or folder starting all the way from the root directory (`/`).
* *example:* `/home/student/Documents`
 
### 9. What is a relative path? Include an example
a relative path is a shortcut address that tells you where a file or folder is based on *where you are right now*.
* *for example:* if you are in your home folder, just typing `Documents/homework-files` is a relative path.
 
### 10. What is the difference between “Your home directory” and “The home directory”?
* *your home directory* is your personal user folder (like `/home/student`), where your own files live. 
* *the home directory* refers to the main folder (`/home`) that holds all the different user accounts home folders on the machine.
