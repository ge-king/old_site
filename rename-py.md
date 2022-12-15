---
layout: post
author: George King
tags: [Python]
title: batch-rename-py
---

## What is it?

`batch-rename-py` is a simple Python3 script that simply renames all files in a directory to the user's required naming scheme. Current naming schemes are:
- `ChosenName-YYYY-MM-DD-HH-MM-SS` where the time and date are of file creation.

## How do I use it?

Download the project with:

```
git clone https://github.com/ge-king/batch-rename-py.git
```

Then install the dependencies:

```
pip install -r requirements.txt
```

To run the project, use the following command:

```
python batch-rename.py
```

You'll then be asked for the path to the directory containing the files to rename. Enter the path.

Then you'll be asked for the filename you want to rename to. The files will be renamed to the required naming scheme.

The program will batch rename all files then close.




## To-do

Future updates will bring:
- More naming schemes.
- Ability to only name select file types.



