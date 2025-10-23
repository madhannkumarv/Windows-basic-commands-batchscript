## Windows-basic-commands-batchscript
## Ex08-Windows-basic-commands-batchscript

## AIM:
To execute Windows basic commands and batch scripting

## DESIGN STEPS:
## Step 1:
Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware

## Step 2:
Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.

## Step 3:
Execute the necessary commands/batch file for the desired output.

## WINDOWS COMMANDS:
Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.

## COMMAND AND OUTPUT
Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.

<img width="746" height="66" alt="386932951-ea175d8a-d7a2-4f82-93c6-d0ba473945cc" src="https://github.com/user-attachments/assets/fc7bdd56-b7eb-4e88-a4fc-444f11596bb7" />


## COMMAND AND OUTPUT
List the contents of the "MyLab" directory.


<img width="686" height="54" alt="386932924-603d0613-2b4f-4187-bcdc-c80a629edc18" src="https://github.com/user-attachments/assets/27955577-00f5-477d-be29-7a97a3024969" />





<img width="777" height="51" alt="386932946-250bd4ac-ddcf-4628-a58e-7f6d405274fd" src="https://github.com/user-attachments/assets/6a464418-375a-43b6-b1c7-c2601edc00d1" />


## COMMAND AND OUTPUT
Copy "MyFile.txt" to a new folder named "Backup" on the desktop.


<img width="746" height="66" alt="386932951-ea175d8a-d7a2-4f82-93c6-d0ba473945cc" src="https://github.com/user-attachments/assets/2667ae5f-5933-4ce3-aa43-113c1906bac2" />



## COMMAND AND OUTPUT
Move the "MyLab" directory to the "Documents" folder.


<img width="952" height="50" alt="386932995-f9ab3537-1f03-48c1-bdfa-f1dd044bd1b7" src="https://github.com/user-attachments/assets/226130a3-0911-4c09-ac92-8aab2d042462" />





<img width="714" height="80" alt="386933017-182e0e1c-dc7e-43f4-b440-88025bddbfdd" src="https://github.com/user-attachments/assets/6a82196e-5d1f-4fcb-b078-b20451464abc" />


## COMMAND AND OUTPUT

<img width="952" height="50" alt="386933117-b358ada1-8d21-486a-9dba-6fb123488c6c" src="https://github.com/user-attachments/assets/55777dbb-ed5a-4ea3-8bc2-f4705abaa66e" />


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop. @echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!

## OUTPUT

<img width="714" height="80" alt="386933093-cf9a4a04-d8d4-4ef7-8f06-2de1a347f830" src="https://github.com/user-attachments/assets/e470e057-0be4-4536-9ddd-80a25a46e704" />


## RESULT:

The commands/batch files are executed successfully.
