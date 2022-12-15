---
layout: post
author: George King
tags: [Python]
title: generate-readme-py
---

## What is it?

`generate-readme-py` is a simple Python3 script that looks in a Python project directory, and attempts to generate a readme file for the project. It does this by firstly creating a `requirements.txt` file for all Python files. This file describes the dependancies required to use the project. The script then writes the `README.md` file, by describing the project files, describing dependancies, detailling installation, and running.

## How do I use it?

Download the project with:

```
git clone https://github.com/ge-king/generate-readme-py.git
```

Then install the dependencies:

```
pip install -r requirements.txt
```

To run the project, use the following command:

```
python generate-readme.py
```




## To-do

Future updates will bring:
- Further file-by-file analysis to automatically find features of the project.



