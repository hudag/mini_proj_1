# Basic Linux Commands

## cd
  * Change directory command. Will change the working directory.
  * This command is used to change the directory you want to work in. You can add new folders or files in a directory of your choice without the use of a mouse. 
  * Here are some examples of the use of the cd command.

  	![cduse](/images/cd_use.PNG)
  	* As shown above there are multiple ways to use the cd command.
		* cd along with the name of the file path can be used to reach any destination directory
		* cd .. changes the directory to the parent directory
		* cd ~ changes the directory to the home directory
## mkdir
  * Make directory command. Makes a new directory in the current directory you are under.
  * This command is used to make a new directory so that you can set different permissions for different directories and so that you are able to easily navigate your files.
  * This is the desktop directory of a computer.

 	![direc](/images/Desktop_files.PNG)
 	* After using the command **mkdir My_New_Directory**, this is the current directory which includes the new directory we have created.

 	![direct](/images/Desktop_files_new.PNG)
## cp
  * Copy command. This command copies files or directories.
  * This makes an exact copy of a file with a different file name. This is useful when you want to have a copy of the original file and create changes on the copy.
  * For example, you have a text file named cat.txt 

   	![cat](/images/cat.PNG)
        
	* You want to make a copy of the file and name it dog
  	* The command used would be **cp cat.txt dog.txt**
  	* Your copied file will be created in your directory shown below

  	![dog](/images/dog.PNG)
## pwd
  * Prints the working directory. Shows where you are currently working, *the directory you are in*.
  * Here is an example of the output of the pwd command.

  	![pwd](/images/pwd.PNG)
## mv
  * The move command. Moves files or directories from one place to another.
  * Usually used to move files  between directories but can also be used to rename a file.
  * To use the mv command to rename a file you would write **mv cat.txt dog.txt**.
    * This changes the name of the file cat.txt to dog.txt
  * To use the mv command to move a file you would write **mv cat.txt pets**
    * The cat.txt file would be moved to the pets directory.
  * This command can be used in a multitude of ways, another example being **mv \*.txt Text_Files**
    * This command would move all the text files from the directory you are working in to the Text_Files folder.
## rm
  * Removes a file or a directory. Can be used to delete just a file or can delete a whole folder and the files inside it.
  * This can be useful if you no longer need the material you created a file for.
  * Here are some examples of this command being used.

  	![rmcat](/images/rmcat.PNG)
	* The **ls** command shows the list of files in the current directory as seen through the first commands output above.
	* The **rm new.txt** command deletes the new.txt file.
	* The **rm -r folder** command deletes the folder directory and all the files it comtains.
	* The file/directory we have removed are no longer shown in the current directory.

![rmcom](/images/rmcom.PNG)

## history
  * The history command. Shows the last commands that you have recently used.
  * This is useful when you need to look at the commands you used a while ago. This command shows a list of the commands you used and the order you used them in.
  * Here is an example of the use of this command.

![image](https://www.howtoforge.com/images/command-tutorial/history-basic-usage.png)
## Home directory and ~
  * The home directory can be accessed through the change directory command, cd. The home directory is shown through the symbol **~** called the tilde.
  * This is used to navigate to the home directory easily. To check if you are in the home directory you can use the pwd command. If there is a ~ then you are in the home directory.
  * To reach the home directory you are able to use the **cd ~** command.
## File paths in Linux
  * The file path the location of a file on a computer. It shows exactly where the file is located, as in which folder path to follow to reach it.
  * Here is an example of a file path, shown in yellow.

   ![path](/images/path.PNG)
## Using the tab key to complete file paths
  * To complete a file path without writing it out completely, a user is able to use the tab key. The tab key is like autofill.








