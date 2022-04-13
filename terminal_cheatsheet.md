# Terminal Command lines
## NAVIGATING
pwd : this command lets you know which folder you are in	

ls : this command displays all the files and folders of the directory you are currently in

ls -l : this extra flag we have added to the ‘ls’ command tells us a little bit more about the files and folders in the directory – mainly the last modification date and file size

ls -a : the ls command doesn’t show us all the files and folders in a directory, some of them are hidden, indicated by the dot before the file, remember you can combine this with the ‘-l’ flag to show the details of ALL files(la -al)

cd : now we know where we are and what files/folders are available we can navigate into a new directory using the change directory, followed by the folder name, so e.g. (cd documents)

~ : after changing directory we can see that there is no longer a tilda (~) symbol which basically acts as a shortcut to go back to the home directory (you can also use ‘cd ~’ or just ‘cd’)

cd - : this takes you back to the directory you were previously in

cd documents/pictures : the cd command can be used to navigate to a different folder as long as you know the pathway. For the example command the terminal would take us to the pictures folder inside documents (have to be separated by forward slash ofc)

‘tab’ key : using the tab key we can use it to autofill a command – usually a file name rather than typing the whole name out, we just do the first few letters

---
## CREATING AND MANIPULATING FILES & FOLDERS

mkdir my_directory : this command stands for make directory, it is followed by the name of the new folder. In naming the new file (or folder) it is best not to use spaces rather underscores or camelCase 

touch my_file.txt : this command creates a new file within the current directory youre in. ‘touch’ is followed by the name of the file ended with a dot and file type

open my_file.txt : this ‘open’ command will open any file or folder, any folder opened will open it in mac finder

mv my_picture.png .. : the ‘mv’ command moves a file, it is followed by 2 pieces of information the file you want to move and the location it is to be moved to. In the example command we have the file my picture and we want to move it. In this example we have used the command of ‘..’ which is a shortcut that means the directory above this one. A single dot ‘.’ Means this directory we’re currently in

mv my_picture.png my_new_picture.png : over here we have used the command mv to rename a file. Since we didn’t specify a location it will rename it and replace it in the same directory

cp my_picture.png my_directory : we can copy files to new locations. First we must specify the file and then the location we want to copy it to. If we had provided a new name in the second path, it would have copied and renamed it as it moved it. If we wanted to copy a directory and its contents we would have had to use the flag ‘-r’ to the cp

rm my_new_picture : this command ‘rm’ is used to delete files, here we have deleted said file

rm -r my_directory : this flag added to the rm command is used to delete directories and their contents

