## **Working on the Assignment**

### **Open the Project**
Go to the Terminal and navigate to `Technology-Projects-BLOCK-1/1.2_logic/01_computers/` folder.

Then, open the folder in your code editor:
```bash
code .
```
Or open manually from *File → Open Folder*

### **Make Changes**

- Modify the first file in `01_hardware_vs_software.md` (the other folder) -- just a minor change.
- Save the changes.

### **Check What Changed**
Before committing:
```bash
git status
```
<img width="732" height="310" alt="image" src="https://github.com/user-attachments/assets/a34786af-942b-4c41-8d69-e0479050e136" />

This shows:
- Modified files
- New files
- Deleted files

---
## **Saving Your Work (Commit)**

### **Add Changes to Staging Area**
To add all changed files:
```bash
git add .
```
<img width="813" height="223" alt="image" src="https://github.com/user-attachments/assets/968a0485-3e77-4cf6-aff8-2450359b307f" />

Or a specific file:
```bash
git add 02_computers/01_hardware_vs_software.md
```
<img width="592" height="90" alt="image" src="https://github.com/user-attachments/assets/11323d10-2d68-4cfc-a67c-86e9035daeaa" />

### **Commit the Changes**
```bash
git commit -m "Completed personal info of lab journal"
```
<img width="877" height="217" alt="image" src="https://github.com/user-attachments/assets/c00de120-48b2-4f29-a28f-d94e222e247f" />

**Good Commit Messages:**
- ✅ "Added README introduction"
- ✅ "Completed Activity 3"
- ❌ "stuff"
- ❌ "update"


### **Repeat Regularly**

Commit:
- After completing each task
- After fixing errors
- Before stopping work

---
## **Uploading Your Work (Push)**

### **Step 16 — Push to GitHub**
Upload commits:
```bash
git push
```
<img width="711" height="259" alt="image" src="https://github.com/user-attachments/assets/a23e0664-7f4d-4649-a7bd-9faa7870202c" />

If it is first push:
```bash
git push -u origin main
```
<img width="497" height="120" alt="image" src="https://github.com/user-attachments/assets/18a77aee-c997-438a-ad15-8e14d491e462" />


### **Step 17 — Verify Submission**
Return to GitHub:
- Refresh the page
- Confirm updated files and latest commit
  <img width="864" height="236" alt="image" src="https://github.com/user-attachments/assets/deca83bf-2da5-40df-b0c6-c8ae13fc4417" />

<img width="684" height="585" alt="image" src="https://github.com/user-attachments/assets/39e8b7f3-afdd-42c2-97b1-3e7a2c00f6bb" />


⚠️ **If it’s not on GitHub, it is not submitted.**

---
## **Continuing Work Later**
When you return:
```bash
cd repository-name
git pull
```
Then continue working.

---
## **Full Workflow Summary**
```bash
git pull
# make changes
git add .
git commit -m "Meaningful message"
git push
```

---
## **Common Problems & Solutions**

### ❌ “Authentication failed”
You may need:
- A GitHub Personal Access Token
- To log in via browser prompt
Follow GitHub authentication steps.

### ❌ “Everything up to date” but changes not online
You probably forgot:
```bash
git add .
git commit -m "message"
git push
```

### ❌ “Merge conflict”
Occurs if:
- You edited on GitHub
- Someone else modified files

Fix:
```bash
git pull
# resolve conflict in file
git add .
git commit
git push
```

---

**Now, following these instructions, complete the whole lab.**
