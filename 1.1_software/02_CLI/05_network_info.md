## ⭐ Activity 5: Networking Basics

### 🎯 Goal  
Explore network tools and check connectivity.

### 📝 Tasks
1. Find your Raspberry Pi’s IP address:
   ```bash
   hostname -I
   ```
   <img width="810" height="118" alt="image" src="https://github.com/user-attachments/assets/b8f0a4c7-a6a9-4d7f-84f7-423bf91a437a" />

2. Check whether your Pi can reach the internet:
   ```bash
   ping google.com
   ```
   <img width="778" height="314" alt="image" src="https://github.com/user-attachments/assets/5543bbd3-a7a9-4f97-8e79-77aedcf535da" />

   (Stop it with **CTRL + C**)

   <img width="636" height="307" alt="image" src="https://github.com/user-attachments/assets/63e0cb6d-aa0c-453d-8332-5a9e147581eb" />

   
3. Display network information:
   ```bash
   ifconfig
   ```
<img width="609" height="94" alt="image" src="https://github.com/user-attachments/assets/3f184c97-1f25-4e27-ad4a-4c2ab03031be" />

4. Troubleshooting Network Commands — Git Bash on Windows
Problem encountered
While completing Activity 5, I attempted to run the Linux networking commands:
hostname -I
ifconfig
Git Bash returned errors:
- hostname -I — unknown option
- ifconfig — command not found
Reason
I am using Git Bash on Windows rather than a Raspberry Pi running Linux. Git Bash supports many Linux-style commands, but some commands and options are different or unavailable.
Alternative commands
To find my laptop’s IP address, I used:
ipconfig
To display detailed network information, I used:
MSYS_NO_PATHCONV=1 ipconfig.exe /all 
Internet connectivity test

What I learned
Different operating systems provide different command-line networking tools. I learned how to identify my computer’s IP address, inspect network settings and test connectivity using Windows alternatives.
Screenshot evidence
- Screenshot showing the successful ipconfig command

  <img width="685" height="324" alt="image" src="https://github.com/user-attachments/assets/94486061-72ad-4088-a948-a7ed499d07c2" />

- Screenshot showing the successful MSYS_NO_PATHCONV=1 ipconfig.exe /all command

<img width="887" height="445" alt="image" src="https://github.com/user-attachments/assets/ad808d20-5571-4d9e-bf77-2efb79f2303b" />

**Upload screenshots for every step**


