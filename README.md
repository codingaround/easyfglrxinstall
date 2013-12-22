easyfglrxinstall
================

Easy Ubuntu fglrx installation script

What can this script do?  
This script was written to help people troubleshoot their fglrx installation faster when it causes problems.  
So instead of manually entering all the commands found on the tutorial pages,  
this script does all the work for you.

It let's you choose between 3 installation methods:
- Downloading and installing fglrx via apt-get
- Creating and installing a debian package for your system
- Simply execute the .run file found in the zip archive downloaded from AMD

If you want to post feedback, improvements or suggestions, feel free to do so at [Ubuntu Forums](http://ubuntuforums.org/showthread.php?t=2174060).

Instructions:

1. Download the appropriate .zip file for your system at [AMD's website](http://support.amd.com/us/gpudownload/Pages/index.aspx).
2. Create a folder and place the .zip file in that folder.
3. Download the script from this repository with any method of your choice.  
   The simplest way is to just click the [`Download ZIP`](https://github.com/netcyphe/easyfglrxinstall/archive/master.zip) button.
4. Save it as easyfglrxinstall.sh in the folder where you saved that zip file.
5. Open a terminal and type the following commands:

    ````
    cd whereever_your_folder_is
    sh easyfglrxinstall.sh
    ````

6. Select either the fast mode or the verbose mode by entering `f` or `v`.
7. Answer the questions by entering `n` for no or `y` for yes.
8. Enjoy!

This script would not be possible without the instructions of the following websites:

- [AskUbuntu](http://askubuntu.com)
- [Linux Tech Tips](http://www.linuxtechtips.com/)
- [Ubuntu documentation](https://help.ubuntu.com/)
- [Unofficial Wiki for the ATI Linux Driver](http://wiki.cchtml.com/)

**Disclaimer:** I cannot be held responsible for any system damage or data loss. Use this script at your own risk!
