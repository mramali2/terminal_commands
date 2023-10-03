# Terminal CheatSheet

## Basic terminal code:

| Syntax | Description |
| ----------- | ----------- |
| pwd | show current file path |
| ls | list folders and files in current directory |
| ls -a | list including hidden folders |
| ls -l | long list |
| cd | takes you to root directory |
| cd [filepath] | takes you to a certain directory |
| cd .. | takes you up a level in the file path |
| mkdir [folder_name] | creates a folder in current directory |
| touch [file_name] | creates file in current directory |
| rm [file_name] | removes selected file(s) |
| rm -r [folder_name] | removes selected folder(s) |
| mv [incorrect_name] [correct_name] | renames file/folder |
| mv [current_file_path] [new_file_path] | moves file/folder |
| cp [file_name] [new_file_path] | copy file to new location |
| cp -r [folder_name] [new_file_path] | copy folder to new location |
| open . | open current directory |

## Git Codes:

| Syntax | Description |
| ----------- | ----------- |
| git init | initialise git repository |
| gst | check status of git repository |
| git add [file_name] | add file to git repo |
| git add --all | add all contents of folder to repo |
| git log | check history of changes to git repo | 
| git commit -m "[Description_of_changes]" | commit changes to repo |
| 1.git remote add origin git@github.com:mramali2/git_intro.git
2.git branch -M main 
3.git push -u origin main | adding first instance to github (only require step 3 for subsequent pushes) |