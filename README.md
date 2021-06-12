---
description: 'To commit,rollback and to merge code changes.'
---

# Git Version Control

## 🐦 Introduction to Version Control

1. Timely changes ,Flexibility.
2. To keep track of the changes.

![](.gitbook/assets/image%20%281%29.png)

## 🐦 Diffing Files

To find the difference / changes made between files / directories

1. **diff** command - to find the difference between two files/ directories.

![](.gitbook/assets/image%20%286%29.png)

**&lt;** --&gt; line /s removed

 **&gt;** --&gt; line /s added

"**-u**" --&gt; unified format   
**Syntax** : diff -u file1.py file2.py 

2."**wdiff** " --&gt; indicates the changes word by word instead of line by line.

3. Graphical tools that highlight content using color in Graphs.  
Commands : meld , kDiff3 , vimdiff \(gives better context to the content\)

## 🐦 Applying changes

1. Syntax : " **diff -u old\_file new\_file &gt; changes.diff** "

Difference in the file are stored in the **changes.diff** .It is also called as **patch file / diff file**. 

2. Command "**patch**" - Takes the content from the **diff file** and apply the changes to the **original file.**

![](.gitbook/assets/image%20%2813%29.png)

![Applying patch command](.gitbook/assets/image%20%2815%29.png)

![Problem fixed!!](.gitbook/assets/image%20%2810%29.png)

##  







