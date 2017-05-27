### Shell-Script
#### This is my first shell script 
#### It is very usefull to organize my
* .cpp
* .c
* .java 
#### files

**HOW TO USE ?**
> chmod +x extension.sh 
#### run this command in terminal (making the file executable)  ,then
> ./extension.sh
#### then all the code files will go into the different different folder (C_FILES ,CPP_FILES ,JAVA_FILES)
**But You can create a symlink ,create it in */usr/local/bin/name_of_new_command.* All you need is to run command**
> sudo ln -s /full/path/to/your/file/ /usr/local/bin/name_of_new_command

**After that you should make your file executable :**
> chmod +x /full/path/to/your/file

**Now you're able to run**
> name_of_new_command

**at any time in your terminal.**


#### When you code in any language ,no matter you just save your code at home directory in linux 
#### and run this code ,it's atomatically move all the files in corresponding folders
