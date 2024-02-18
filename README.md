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

create_file.sh: wget https://raw.githubusercontent.com/DprinceG/FileOrganizer/4b6f2074825aad7d6b6b2425597d705898228057/create_files.sh

To organize the file: 
file_organizer.sh: wget https://raw.githubusercontent.com/DprinceG/FileOrganizer/main/file_organizer.sh






