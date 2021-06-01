# File-Explorer-Application
A fully functional File Explorer Application, albeit with a restricted feature set.
It works in two mode Normal Mode and Command mode 
  1. Normal Mode used to explore the current directories and navigate the file System.
  2. Command Mode- used to enter shell commands.

The root of the application is where it is strted.
The display data in line line in command line and shows the permision related to it.

# Normal Mode
  Normal mode is default mode of the application .It has following functionalities 
  a.Every file in the directory is displayed on a new line with the features like 
                 i.File Name
                 ii. File Size
                 iii. Ownership and Permissions
                 iv. Last Modified 
                 
  b.It shows "." and ".." for current and parent directories 
  c.The file explorer handle scrolling in the case of verical overflow using k & I
  d. User is able to navigate the cursor up down arrows.
  e. When key is pressed the Directory is opened and list is refreshed 
  
  # Command mode
   The application changes to command line on press of ":" button .
   It has following functionalities
    a. Copy -Copy - 
     ‘copy <source_file(s)> <destination_directory>’
     'Move - ‘move <source_file(s)> <destination_directory>’
     'Rename - ‘rename <old_filename> <new_filename>’
     b. Create File 
     ‘create_file <file_name> <destination_path>’
     c. Delete File 
     delete_file <file_path>’
     d.Goto -'goto <location'
     ‘goto <location>’.
     e. Search -'search<file_name>' or search<directory_name>
       output as found and not found .
  
  Header file used are 
  1.Dirent.h -  This facilitates directory traversing.
  2 Termios.h - To control canonical and non canonical form of terminal and to manipulate echo for the cursor movemment .
  4. sys/stat.h --The <sys/stat.h> header defines the structure of the data returned by the functions fstat(), lstat(), and stat().

  
