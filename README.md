
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/DPotoyan/Chem563/master)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github//DPotoyan/Chem563/blob/master/00_Welcome2Chem563.ipynb)

# Materials for the course Chem563: Statistical Mechanics, ISU Spring 2021 

**Instructor:** Davit Potoyan

---

### 0. What is in this repository?

This repository contains computational notebooks for the course Chem563 Intro to Stat Mech taught at Iowa State University. The content is broken up into (hopefully) self-contained units organized by a distinct topic. Inside each unit you will find the following materials:

1. Lecture slides giving brief summary of key ideas and equation. This is for quick reviewing of discussed material.
2. PDF files of relevant research papers, book chapters and other extra reading material. This is for bedtime reading.  
3. Jupyter-notebooks `notebook.ipynb` and some python files `file.py` containing short snippets for doing various numerical experiments.

### 1. How to run notebooks?

- Open them in GoogleCollab. Cons: No installation required just open and run. Pros: notebooks have to live in GoogleDrive

- Download files, create a separate conda environment using `enviroanment.yml` and run notebooks locally in your computer. Cons: notebooks are stored locally with more controll over files and environments. Pros: will be using local memory for comptutation.


### 2. How to use git to update local copy of the repository

We will be adding new material and folders will be populated with new notebooks as we go through the course. 

For the first time clone course repository repository
```bash
$ git clone https://github.com/DPotoyan/Chem563.git
```
A new folder called Chem563 will be created. Enter it and run `jupyter-notebook` or `jupyter-lab`
```bash
$ jupyter-lab 
```

To update your local copy do the following (overwrites the contents so keep a separate folder for your own files, HW, projects etc): 

```bash
$ cd  Chem563/
$ git pull
```
