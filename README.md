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
![image](https://github.com/salinianbzhgan/Windows-basic-commands-batchscript/assets/145742862/1c32f848-43bb-444b-aee7-d6d980bfc1a0)

## COMMAND AND OUTPUT

List the contents of the "MyLab" directory. cd %userprofile%\Desktop\MyLab
![image](https://github.com/salinianbzhgan/Windows-basic-commands-batchscript/assets/145742862/c256e3a2-7cec-4586-bde6-7d831f20419b)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop. dir %userprofile%\Desktop\MyLab

![image](https://github.com/salinianbzhgan/Windows-basic-commands-batchscript/assets/145742862/f3c6b2b9-80fa-436b-99f4-a3f24c3ca384)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder. mkdir %userprofile%\Desktop\Backup mkdir %userprofile%\Desktop\Backup
![image](https://github.com/salinianbzhgan/Windows-basic-commands-batchscript/assets/145742862/1241dbd2-1cd2-43ef-8a0c-c1583a289a87)
![image](https://github.com/salinianbzhgan/Windows-basic-commands-batchscript/assets/145742862/97bb0f57-05f0-4f2b-bf1e-8ef89a0ffdff)


## COMMAND AND OUTPUT
mv Myfile.txt %userprofile%\Documents
![image](https://github.com/salinianbzhgan/Windows-basic-commands-batchscript/assets/145742862/d4178a96-401a-4e04-9a4f-c4b8085196e6)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!
## OUTPUT



![image](https://github.com/salinianbzhgan/Windows-basic-commands-batchscript/assets/145742862/4cf51efd-b81f-40d9-9492-e2e87c6f1dbc)



# RESULT:
The commands/batch files are executed successfully.

