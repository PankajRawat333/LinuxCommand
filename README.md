# LinuxCommand

>ifconfig (Interface configuration)- to check linux system connectivity

>clear - to clear terminal

>apt-get update - update system packages

>uname - get version name

>uname -r - get detail version name

>uname -a - get all detail

>history - get all recent commond 

>ls - list the directory

>cd .. - go back in once directory

>/# - user directory

>~cd - root directory

>touch - to create new file (e.g. touch test.txt)touch, It's the equivalent command of mkdir for files. You can create a blank file with touch command.

>rm - remove file or directory (e.g. rm test.txt)

>rmdir - remove directory

>mkdir - make directory (mkdir <directoryName>)

>rmdir - to remove directory(rmdir <directoryName>)

>man ls (open manual of commond)

>cp test <destination directory> - copy file

>ls -l test - list of all permission for file

Permission
	Admin - rwx (4+2+1=7)
	Group - xr  (4+2=6)
	public - x  (=4)
read,write and executable

permission by number
1 executable
2 write
4 read
1+2+3 =7 

chmod 764 <fileName> - change permission
	
	
>pwd - This command prints the location of your current working directory.

>cat - It's used to print the contents of a file to the screen(stdout more precisely), really useful when you want to have a quick look on contents of a file. As example, use cat a_text_file to get the inside contents of that file in your screen.

>mv- The mv command is used to move or rename directories and files. To rename a file use mv old_name new_name.

>free - The free command is used to display amount of free and used RAM in the system, also prints the swap space stats.

>zip - No doubt you often need to create and extract zip archives, here's the zip and unzip commands for that.
Most probably these commands are not pre-installed, install them with apt in Ubuntu.

sudo apt-get install zip unzip

The syntax to create a zip archive,

zip -9r my_archive.zip  file_1 file_2 folder_1 folder_2 folder_3

>unzip - The unzip command extracts archives to the current working directory(pwd) by default. So if you need to extract the contents to a specific folder, then use

unzip my_archive.zip -d /path/to/my_directory

> Shutdown - 

shutdown -h now to power off immediately.

shutdown -h +10 to shutdown after 10 minutes.

reboot to reboot the machine immediately.
