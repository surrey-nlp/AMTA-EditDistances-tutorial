<p align="center"><img src="imgs/ctsnewlogo-w.png" alt="logo" width="190" height="100"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="imgs/aisurrey.svg" alt="logo" width="250" height="120"/></p>

# AMTA 2024 Tutorial: Edit Distances and their application to downstream tasks, in research and commercial contexts.

## Overview

This repository contains the code and resources for our tutorial presented at the **16th Biennial Conference of the Association for Machine Translation in the Americas (AMTA 2024)**. The tutorial covers the theoretical foundations of edit distances, their applications in Natural Language Processing (NLP), and the challenges and limitations when applying these metrics to tasks like Machine Translation (MT), Quality Estimation (QE), and Automatic Post-Editing (APE).

## Tutorial Outline

The tutorial is structured into four parts:

1. **Part 1: Edit distances and their different implementations and applications**

2. **Part 2: Analysing an incrementally-complex sequence of edits**
   
3. **Part 3: Building a Computational Perspective**
   
4. **Part 4: Implications for research and commercial applications of edit distances**
   
## Repository Structure

- `code/`: Contains Python notebook used during the tutorial, including:
  - Examples for calculating Levenshtein, Damerau-Levenshtein, LCS, and N-gram distances.
  - Examples for computing TER (using multiple implementations), BLEU, and chrF score calculations.
  - Scripts for visualizing the results of different metrics using plots and charts.
  
- `data/`: Example dataset used in the tutorial, which include the reference and hypothesis translations for analysis in two separate files.

- `AMTA-ED-Tutorial-2024.pdf`: Slide deck used for presentation. 

## Execute on Google Colab

Click here to open the code in Google colab: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/surrey-nlp/AMTA-EditDistances-tutorial/blob/main/code/AMTA_tutorial_ED.ipynb)
