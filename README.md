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

![Screenshot 2024-05-07 220711](https://github.com/Krishna23013541/Windows-basic-commands-batchscript/assets/149557764/1dba6e96-e2f3-4795-aa5d-b87520ba6a08)

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.

## COMMAND AND OUTPUT

![Screenshot 2024-05-07 220755](https://github.com/Krishna23013541/Windows-basic-commands-batchscript/assets/149557764/8edf3a44-6069-4975-ad0e-fbcb23265d00)
![Screenshot 2024-05-07 220830](https://github.com/Krishna23013541/Windows-basic-commands-batchscript/assets/149557764/a22b3329-6bf4-4e13-a654-1cb2108b0c71)

List the contents of the "MyLab" directory.

## COMMAND AND OUTPUT

![Screenshot 2024-05-07 220912](https://github.com/Krishna23013541/Windows-basic-commands-batchscript/assets/149557764/48fd0101-c404-44d6-81fe-8497dfc4a768)

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

## COMMAND AND OUTPUT

![Screenshot 2024-05-07 220956](https://github.com/Krishna23013541/Windows-basic-commands-batchscript/assets/149557764/14a1bfa5-34c5-4d0a-a75a-e01538a31166)
![Screenshot 2024-05-07 221028](https://github.com/Krishna23013541/Windows-basic-commands-batchscript/assets/149557764/8e9a1479-1a46-4ae5-9917-0951bbd1fdd1)

Move the "MyLab" directory to the "Documents" folder.

## COMMAND AND OUTPUT

![Screenshot 2024-05-07 221111](https://github.com/Krishna23013541/Windows-basic-commands-batchscript/assets/149557764/e6b8b60c-77b4-4cbf-9dd8-34d765d9ca5c)

## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!
```

Modify the script to delete files with the ".docx" extension from the "Documents" folder after creating the backup.

```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\*.docx
echo Backup and deletion completed successfully!
```

## OUTPUT

![Screenshot 2024-05-07 221152](https://github.com/Krishna23013541/Windows-basic-commands-batchscript/assets/149557764/86889546-78f7-4c25-a4e5-7c8e94ae3e4a)

# RESULT:
The commands/batch files are executed successfully.

