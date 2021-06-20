# PlagiarismDetection

author: Kamila Kolpashnikova

Project creating a decision tree model in detecting plagiarism in students' work

## Plagiarism Detection (Decision Tree Model)

In this project, I build a plagiarism detector that examines an answer text file and performs binary classification; labeling that file as either plagiarized or not, depending on how similar that text file is to a provided Wikipedia source text. 

This project involves a few discrete steps:

* Clean and pre-process the data.
* Define features for comparing the similarity of an answer text and a source text, and extract similarity features.
* Select "good" features, by analyzing the correlations between different features.
* Create train/test subsamples 
* Train a decision tree classifier

## Project Background

This project was done as a part of ML Engineer certification program.

## Data

This data is a slightly modified version of a dataset created by Paul Clough (Information Studies) and Mark Stevenson (Computer Science), at the University of Sheffield. You can read all about the data collection and corpus, at [their university webpage](https://ir.shef.ac.uk/cloughie/resources/plagiarism_corpus.html). 

> **Citation for data**: Clough, P. and Stevenson, M. Developing A Corpus of Plagiarised Short Answers, Language Resources and Evaluation: Special Issue on Plagiarism and Authorship Analysis, In Press. [Download]

## Model

A Decision Tree model with 96% accuracy.