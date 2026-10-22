
## ⭐ Activity 4: Basic System Info

### 🎯 Goal  
Use CLI commands to inspect your system.

### 📝 Tasks
1. Check your current username:
   ```bash
   whoami
   ```
   <img width="620" height="102" alt="image" src="https://github.com/user-attachments/assets/7cdb3e5a-cfba-4ced-997f-042f703fbcbd" />

2. Check disk storage:
   ```bash
   df -h
   ```
   <img width="567" height="157" alt="image" src="https://github.com/user-attachments/assets/f3c204b7-296f-4a2f-9a8d-5c55c00d1216" />

3. Check RAM usage:
   ```bash
   free -h
   ```
<img width="597" height="102" alt="image" src="https://github.com/user-attachments/assets/ca1ea7ff-d06c-4ab1-bc6d-1d87a67b7ece" />

4. Troubleshooting RAM Usage Command — Git Bash on Windows

Problem encountered:

I attempted to check RAM usage using the Linux command:

free -h

However, Git Bash returned the following error:

bash: free: command not found

Reason:

The free command is commonly available on Linux but is not included in my Git Bash installation on Windows.

Alternative solution:
```bash
powershell.exe -NoProfile -Command "Get-CimInstance Win32_OperatingSystem | Select-Object TotalVisibleMemorySize,FreePhysicalMemory"
```
<img width="661" height="208" alt="image" src="https://github.com/user-attachments/assets/bac4945a-1354-40d3-a4ff-fef743d56128" />



I used Git Bash to execute a Windows PowerShell command:
**Upload screenshots for every step**


