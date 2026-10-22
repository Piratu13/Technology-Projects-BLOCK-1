
## ⭐ Activity 2: Creating and Managing Files

### 🎯 Goal  
Practise working with files and folders.

### 📝 Tasks

0.1 Move University repository to one drive:

<img width="1165" height="108" alt="image" src="https://github.com/user-attachments/assets/817f0b26-f3ea-4bd6-9ee5-30ec01b0735f" />

0.2 Set the actual OneDrive folder name, find the needed folder automaticly and Test path destination:

<img width="1198" height="241" alt="image" src="https://github.com/user-attachments/assets/c68a8c9e-6208-4c04-8645-5efb3fd77c3d" />

<img width="1248" height="281" alt="image" src="https://github.com/user-attachments/assets/5c3ddd0e-4c6c-4ad6-a286-9d8e441ae81c" />


0.3 Verifying the new Location:

<img width="1330" height="282" alt="image" src="https://github.com/user-attachments/assets/9e09eddd-51d4-4ac8-b593-ef45bf59b97c" />



*Push everything to your GitHub assigment. Make as many commits as needed.*

1. Create a new folder called `practice` in your CLI directory:
   ```bash
   mkdir practice
   ```
   <img width="1494" height="370" alt="image" src="https://github.com/user-attachments/assets/860ec32f-0fb5-4c9c-b6f4-463226103a0a" />

2. Move into it:
   ```bash
   cd practice
   ```
   <img width="1500" height="193" alt="image" src="https://github.com/user-attachments/assets/8aa0db23-5624-4839-b58f-454d498899f4" />

3. Create two files:
   ```bash
   touch file1.txt file2.txt
   ```
   # CLI Practice — PowerShell vs Git Bash

## Problem encountered

While completing the Managing Files activity, I attempted to create two files using:

`touch file1.txt file2.txt`

PowerShell returned an error stating that `touch` was not recognised as a command.


## What I learned

The `touch` command is commonly available in Linux shells and Git Bash, but it is not a standard PowerShell command.

PowerShell uses an alternative command:

`New-Item file1.txt, file2.txt -ItemType File`

## My solution

I switched the VS Code terminal from PowerShell to Git Bash so I could practise the Linux-style commands used in the university activity.

I then continued the file-management exercises using Git Bash.

## Evidence

- Screenshot of the PowerShell error

<img width="1541" height="214" alt="image" src="https://github.com/user-attachments/assets/c64b1eb5-e776-47a9-97d1-4b58b7a1e251" />
  
- Screenshot of the successful commands in Git Bash

<img width="1041" height="203" alt="image" src="https://github.com/user-attachments/assets/f8d10747-6f9e-411a-ab43-53719b66f56a" />

  
4. Rename `file1.txt` to `notes.txt`:
   ```bash
   mv file1.txt notes.txt
   ```
   <img width="714" height="120" alt="image" src="https://github.com/user-attachments/assets/45d01cc5-3771-419c-bcc2-eb387a6a44f6" />

5. Copy `notes.txt` to a new file called `notes_backup.txt`:
   ```bash
   cp notes.txt notes_backup.txt
   ```
6. Delete `file2.txt`:
   ```bash
   rm file2.txt
   ```

