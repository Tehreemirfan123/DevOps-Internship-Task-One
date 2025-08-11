# Task One Documentation

This repository contains two files for the Week 1 Git task. 
File 1 and File 2 were created, pushed, and File 1 was later updated.

---

## 1. Created a folder named Internship-Task-One
Used mkdir command to make new directory 

`mkdir Internship-Task-One`

`cd Internship-Task-One`

---

## 2. Created two files
Used touch command for both files

`touch File-1.txt File-2.txt`

---

## 3. Add content in files
Used command vi to write to files

`vi File-1.txt`

File 1 contains content regarding paragraph writing.

`vi File-2.txt`

File 2 contains paragrapgh on global warming.
Saved both files. Checked git status which says git is not initialized yet.

---

## 4. Initialize git 
Used init command 

`git init`

Output: Initialized empty Git repository in C:/Users/Tehreem Irfan/Documents/Learn Git/Internship-Task-One/.git/

---

## 5. Stage Files 
Used git add command

`git add .`

This stages both files to be committed.

---

## 6. Commit Files
Used git commit to commit the final files

`git commit -m "Add two files"`

Output: $ git commit -m "Add two files"
[main (root-commit) 334d445] Add two files
 2 files changed, 106 insertions(+)
 create mode 100644 File-1.txt
 create mode 100644 File-2.txt

---

## 7. Finally add and push to remote repository 
Made a repository on github account named Cloud-Internship-Task-One

`git remote add origin "https://github.com/Tehreemirfan123/Cloud-Internship-Task-One.git"`

`git push origin main`

---

## 8. Modify File 1 and add changes 
Modified File-1.txt by adding a  paragrapgh oon importance of education using vi command.

`vi File-1.txt`

`cat File-1.txt`

`git add file-1.txt` 

Stage the file again to be committed.

`git commit -m "Add a paragraph on Importance of Eduacation"`

`git push origin main`

---

## 9. Check Status
Checks the status again before final submission

`git status`

---

## 10. Add Readme.md
Using touch 

`touch Readme.md`

Add and push to remote repository

`git add Readme.md`

`git commit -m "Add a Readme file"`

`git push origin main`

---