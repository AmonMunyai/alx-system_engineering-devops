# 0x00-shell_basics
Descriptions about what each script is doing.

## Mandatory

* **0-current_working_directory** - Print's the absolute path name of the current working directory.
* **1-listit** - Display's the contents list of your current working directory.
* **2-bring_me_home** - Change's the working directory to the user's home directory.
* **3-listfiles** - Display's current working directory in a long format.
* **4-listmorefiles** - Display's current working directory contents, including hidden files (starting with .). Using long format.
* **5-listfilesdigitonly** - Display's current working directory contents in a long format, with user and group IDs displayed numerically, and hidden files (starting with .).
* **6-firstdirectory** - Create's a directory named ```my_first_directory``` in the ```/tmp/ directory```.
* **7-movethatfile** - Move's the file betty from ```/tmp/``` to ```/tmp/my_first_directory```.
* **8-firstdelete** - Delete's the file betty, that is in ```/tmp/my_first_directory```.
* **9-firstdirdeletion** - Delete's the directory ```my_first_directory``` that is in the ```/tmp``` directory.
* **10-back** - Changes's the working directory to the previous one.
* **11-lists** - List's all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the ```/boot``` directory (in this order), in long format.
* **12-file_type** - Print's the type of file named ```iamafile```. Which is located in the ```/tmp``` directory.
* **13-symbolic_link** - Create's a symbolic link to ```/bin/ls```, named ```__ls__```. The symbolic link is created in the current working directory.
* **14-copy_html** - Copies all the HTML files from the current working directory to the parent of the working directory, but only copies files that did not exist in the parent working directory or were newer than the versions in the parent of the working directory.

## Optional

* **100-lets_move** - Move's all files beginning with an uppercase letter to the directory ```/tmp/u```.
* **101-clean_emacs** - Delete's all files in the current working directory that end with the character ```~```.
* **102-tree** - Create's the directories ```welcome/```, ```welcome/to/``` and ```welcome/to/school``` in the current directory.
