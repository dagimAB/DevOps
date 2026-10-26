# Week 1 Linux Hands-on Lab

This repository documents the completion of the Week 1 Linux Hands-on Lab tasks for the Cloud & DevOps track. 


## Task Completed and Commands Used

### 1. Create the Workspace Directory
Created the `cloud-devops/week1` nested directory structures:
```bash
mkdir cloud-devops
cd cloud-devops
mkdir week1
cd week1
```

### 2. Create `notes.txt`
Created the file, added text and content.
```bash
touch notes.txt
echo "Hello world" >> notes.txt
cat notes.txt
```

### 3. Organize Project Directory Structure
Created a separate tracking directory and moved the project notes inside it:
```bash
mkdir scripts
mv notes.txt scripts/
```

### 4. Search for the File

```bash
cd scripts
find -name "notes.txt"
```
**Output:** `./notes.txt`

### 5. Find a Running Process and Identify its PID
The process mapping was successfully completed using the `ps aux` fallback command:
```bash
ps aux
```




