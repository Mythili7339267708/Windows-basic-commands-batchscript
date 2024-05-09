# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.



![image](https://github.com/Mythili7339267708/Windows-basic-commands-batchscript/assets/144260246/13ecec61-daed-4ab7-8b0c-a07379d88f28)


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.


![image](https://github.com/Mythili7339267708/Windows-basic-commands-batchscript/assets/144260246/77d35706-9e10-4469-80c8-9751619dddc2)



![image](https://github.com/Mythili7339267708/Windows-basic-commands-batchscript/assets/144260246/78b4f681-d378-4286-9cb6-b8752f44d366)



## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

![image](https://github.com/Mythili7339267708/Windows-basic-commands-batchscript/assets/144260246/11e0e306-fd03-4ad3-bab0-d0c7f2695498)


## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.

![image](https://github.com/Mythili7339267708/Windows-basic-commands-batchscript/assets/144260246/a0023c36-7056-4513-95e7-d6f9f394224f)



![image](https://github.com/Mythili7339267708/Windows-basic-commands-batchscript/assets/144260246/5fa8666c-aab0-46d2-898b-dd2fb804371e)


## COMMAND AND OUTPUT


![image](https://github.com/Mythili7339267708/Windows-basic-commands-batchscript/assets/144260246/713091b6-88ec-499b-b63a-99f92ba93622)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.


```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!

```

```

@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\*.docx
echo Backup and deletion completed successfully!

```




## OUTPUT


![image](https://github.com/Mythili7339267708/Windows-basic-commands-batchscript/assets/144260246/c3f497ce-128a-4af2-8f9e-3c6f5bd3d61c)



# RESULT:
The commands/batch files are executed successfully.

