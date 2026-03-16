# Essential maintainance
1. pkg update: Updates the list of available packages
2. pkg upgrade: Upgrades all your installed packages to the latest version
3. termux-setup-storage: Grants Termux permission to access your phone’s internal storage
 
# File और Dir management
 1. pwd :Print Working Directory (shows where you are)
 2. ls :List files and folders in the current directory
 3. ls -a :list all
 4. cd <folder> :Change Directory (e.g., cd /sdcard)
 5. mkdir <name> Make a new directory (folder)
 6. rm <file> :Remove a file
 7. rm -rf <folder> :Forcefully delete a folder and everything inside it. (Use with caution!)
 8. cp <source> <dest> :Copy a file or folder
 9. mv <source> <dest> Move or rename a file or folder
 
 # system info
 1. clear: Clears the terminal screen (great for when things get messy)
 2. top: Shows real-time system processes (CPU/RAM usage)
 3. whoami: Tells you your current user ID
 4. exit: Closes the Termux session.

 # Installing tools
1. pkg install git: To clone projects from GitHub
2. pkg install python: To run Python scripts
3. pkg install nano: A simple, beginner-friendly text editor
4. pkg install curl or wget: For downloading files from the internet via URL
5. `pkg install which` path batane ke liye `which fileName`

# other
1. Ctrl + C :kill the task
2. Tab Key: Start typing a filename and hit Tab. Termux will auto-complete it for you
3. Up/Down Arrows: Cycles through your command history so you don't have to re-type long commands
4. Search : `pkg search <query>`
5. termux-wake-lock
6. `chmod +x apktool <fileName>` : executive permission
7. `<pkg> -v` :showVersion