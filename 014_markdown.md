# Title: Practical Assignment #1 - Linux Basics & File Viewing
---
## 1. Create a directory named linux_assignment1. Inside it create files notes.txt, tasks.txt, and data.csv.Display your current location.
### Ans
```base
mkdir linux_assignment1 && cd linux_assignment1 && touch notes.txt data.csv && pwd
```
---
## 2. Copy notes.txt to notes_backup.txt. Rename tasks .txt to dodo.txt. List all files in the directory.
### Ans
```base
cp notes .txt notes_backup.txt && mv tasks.txt todo.txt && ls
```
---
## 3. Add at least 10 lines of text to todo.txt Display the first 3 lines and the last 3 lines.
### Ans
```base
head -n 3 todo.txt && tail -n 3 todo.txt
```
---
## 4. Create a directory named named archive.Move_notes_backup.txt and data.csv into archive. Verify the contents of archive.
### Ans
```base
mkdir archive && mv notes_backup.txt data.scv archive/ && ls archive
```
---
## 5. Display your command history, clear the screen, and finallly print your current working directory.
### Ans
```base
pwd
```
