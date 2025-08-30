# Install Git on Windows 10
- First check if it's already installed
- Type this command on Windows Powershell
- git --version
- ![git installation windows](images/image018.png)
- If Powershell shows you some version that means it's already installed, but if it shows something like this image below, continue with the installation
- ![git installation windows](images/image004.png)
- Download Git
- https://git-scm.com/downloads
- On the first installation window, choose NONE, you don't want a credential helper
- Unmark the option for graphical interface
- ![git installation windows](images/image003.png) 
- If you already use VS Code, Notepad or another modern editor, choose it, Vim is frustrating for beginners.
![git installation windows](images/image023.png)
- Select override the default branch name for new repositories and use "main" 
![git installation windows](images/image024.png)
- Choose Git from the command line and also from 3rd-party software (like VSCode)
- ![git installation windows](images/image005.png)
- Select "Use bundled OpenSSH" so that Git has everything it needs to function correctly
- ![git installation windows](images/image025.png)
- Select "OpenSSL library", you should only choose "Use the native Windows Secure Channel library" if you are in a corporate or managed environment where you know that your organization's internal certificates 
- ![git installation windows](images/image026.png)
- Select "Checkout Windows-style, commit Unix-style line endings" because you're running Windows.
- ![git installation windows](images/image027.png)
- Use MinTTY
- ![git installation windows](images/image006.png)
- Select "Fast-forward or merge" if you're not very experienced
- ![git installation windows](images/image028.png)

- For a standard, general-purpose installation, the best choice is to leave "Enable file system caching" checked and leave "Enable symbolic links" unchecked unless you have a specific need for them.
- ![git installation windows](images/image029.png)
- Choose NONE for credential manager
- ![git installation windows](images/image007.png)
- Once installed, when you right-click on any folder in Windows File Explorer, the "Git Bash here" option should appear in the context menu.
- ![git installation windows](images/image008.png)
- By choosing Git Bash, you'll open the terminal to type Git commands
- ![git installation windows](images/image009.png)