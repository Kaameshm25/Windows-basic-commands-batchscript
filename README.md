# Windows-basic-commands-batchscript

# Ex08-Windows-basic-commands-batchscript

## AIM :

To execute Windows basic commands and batch scripting

## DESIGN STEPS :

### Step 1 :

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2 :

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.

### Step 3 :

Execute the necessary commands/batch file for the desired output. 

```
DEVELOPED BY :Kaamesh M
REG NO : 212223040080
```
## WINDOWS COMMANDS :
## Exercise 1: Basic Directory and File Operations

Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT :

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
mkdir %userprofile%\Desktop\MyLab

![OS EX 08 (1)](https://github.com/Kaameshm25/Windows-basic-commands-batchscript/assets/144870650/01588ade-bd6e-4d7f-8000-ea4ebdbbf88b)


## COMMAND AND OUTPUT :

List the contents of the "MyLab" directory.
cd %userprofile%\Desktop\MyLab

![OS EX 08 (2)](https://github.com/Kaameshm25/Windows-basic-commands-batchscript/assets/144870650/3248f7f4-c579-4eea-ae85-59fe80c9fe2b)

![OS EX 08 (3)](https://github.com/Kaameshm25/Windows-basic-commands-batchscript/assets/144870650/5e828262-9d64-4cb4-8474-72f4548aab77)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
dir %userprofile%\Desktop\MyLab

![OS EX 08 (4)](https://github.com/Kaameshm25/Windows-basic-commands-batchscript/assets/144870650/e1a5890c-4f42-4ca6-aeb7-fd62c0babed3)


## COMMAND AND OUTPUT :

Move the "MyLab" directory to the "Documents" folder.
mkdir %userprofile%\Desktop\Backup
mkdir %userprofile%\Desktop\Backup

![OS EX 08 (5)](https://github.com/Kaameshm25/Windows-basic-commands-batchscript/assets/144870650/265bcc00-eb8b-419a-b709-cdf44cb52949)


![OS EX 08 (6)](https://github.com/Kaameshm25/Windows-basic-commands-batchscript/assets/144870650/7eb5214a-edb8-4d29-bcec-fd62a3ac63c5)


## COMMAND AND OUTPUT :

mv Myfile.txt %userprofile%\Documents

![OS EX 08 (7)](https://github.com/Kaameshm25/Windows-basic-commands-batchscript/assets/144870650/e11f8b43-26fb-4543-9968-02feb0fbefcc)


## Exercise 2: Advanced Batch Scripting

Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!

## OUTPUT :

![OS EX 08 (8)](https://github.com/Kaameshm25/Windows-basic-commands-batchscript/assets/144870650/5f3ee1f4-4f44-40c0-ab77-5356a63d226b)


## RESULT :
The commands/batch files are executed successfully.

