# FileOrganizer
script that organizes files
---------
Project Name: File Organizer

Project Description:
Create a bash script that organizes files in a specified directory based on their file extensions. The script will scan the target directory, identify the type of each file based on its extension, and then move the files into corresponding subdirectories based on their types. 

For example, all ".jpg" files will be moved to a "Pictures" folder, all ".mp3" files to a "Music" folder, etc.

Requirements:

The script should take the target directory as an argument, and if no argument is provided, it should use the current directory.
The script should create subdirectories for different file types (e.g., "Pictures," "Music," "Documents," "Videos," etc.) if they don't already exist.
It should handle files with no extensions or unknown extensions by moving them to a "Misc" folder.
The script should display appropriate messages for each action taken (e.g., "Moving file.jpg to Pictures folder," "Creating Music folder," etc.)
The script should be able to handle spaces and special characters in filenames and directory names.


Implementation
Before writing the actual script, we will need the files with different extensions available in the directory.

First we will create those files by using the script from the below link. 
Here we will pull the file named ‘create_files.sh’ from github that consists of the script:

To create the file 

create_file.sh: wget https://raw.githubusercontent.com/DprinceG/FileOrganizer/main/create_files.sh

<img width="657" alt="image" src="https://github.com/DprinceG/FileOrganizer/assets/160339594/c05bab08-557c-40f6-bb7d-6322aba71e0e">


if you wish to view the file content then use the command cat create_file.sh

To run the bash script first we need to set permission so that we can excute the it.
command: chmod +x create_files.sh
To check you have the right permission 
command: ls -lthr

<img width="378" alt="image" src="https://github.com/DprinceG/FileOrganizer/assets/160339594/e38b1317-955a-4bcf-bea1-625fb60b2ec6">

Now run lets run the bash script:

<img width="322" alt="image" src="https://github.com/DprinceG/FileOrganizer/assets/160339594/672774ce-5a38-4e43-88f2-dfde8d40db0a">

Let check if the file get created.

<img width="593" alt="image" src="https://github.com/DprinceG/FileOrganizer/assets/160339594/33b0bb13-2242-4765-aa86-cd2c69e27a4d">





To organize the file: 
file_organizer.sh: wget https://raw.githubusercontent.com/DprinceG/FileOrganizer/main/file_organizer.sh


Test






