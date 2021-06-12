# Undoing Things

## 🐦 Undoing changes before commiting

1. git **checkout** branch / file name  &lt;&lt; to revert back&gt;&gt;
2. git **reset** &lt;&lt; changes made in the staging area and we dont want to commit rather not need in such case&gt;&gt;
3. git **add \*** &lt;&lt; Changes done in working tree are all reflected to the staging area&gt;&gt;

    4. **-p flag** is used for individual change by change instead of the whole file check

## 🐦 Amending commits

1.git **commit --amend** &lt;&lt;What if we commited and wanted to roll back? &gt;&gt;

## 🐦 Rollbacks

1. git **revert** **HEAD**&lt;&lt;If a bad comment was added and in the revert the bad comment will be deleted&gt;&gt;

## 🐦 Identfying a Commit

1. commit id is called "**HASH**" constructed using **SHA1**  Algorithm &lt;&lt;Gets the dats from commit and converts into 14 digit form &gt;&gt;



