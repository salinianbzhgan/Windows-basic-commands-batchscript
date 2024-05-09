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

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it. %userprofile%\Desktop\MyLab 
![image](https://github.com/salinianbzhgan/Windows-basic-commands-batchscript/assets/145742862/5dbcef40-30e4-4572-b643-28570249112f)


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory. cd %userprofile%\Desktop\MyLab
![image](https://github.com/salinianbzhgan/Windows-basic-commands-batchscript/assets/145742862/8538f3b6-b674-4697-92d3-d5cd764bea6c)
![image](https://github.com/salinianbzhgan/Windows-basic-commands-batchscript/assets/145742862/99f780f0-ece2-4daa-8c61-cbac60dd0467)

## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop. dir %userprofile%\Desktop\MyLab
![image](https://github.com/salinianbzhgan/Windows-basic-commands-batchscript/assets/145742862/97459805-54e9-438e-97e9-67786c4354b7)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder. mkdir %userprofile%\Desktop\Backup mkdir %userprofile%\Desktop\Backup
![image](https://github.com/salinianbzhgan/Windows-basic-commands-batchscript/assets/145742862/4e6f4a78-0039-4b8f-99cd-1299cc3e4d1b)
![image](https://github.com/salinianbzhgan/Windows-basic-commands-batchscript/assets/145742862/152dc373-23b1-48c6-baa0-3513a4c1ab70)


## COMMAND AND OUTPUT
mv Myfile.txt %userprofile%\Documents
![image](https://github.com/salinianbzhgan/Windows-basic-commands-batchscript/assets/145742862/98cf2c04-e254-4e8f-abe2-63c1c4b96e04)

## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!
## OUTPUT
![image](https://github.com/salinianbzhgan/Windows-basic-commands-batchscript/assets/145742862/cafac344-7f4a-43c8-9c6b-5499cc210dd7)





# RESULT:
The commands/batch files are executed successfully.

