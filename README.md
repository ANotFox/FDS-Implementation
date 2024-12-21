# FDS-Implementation

An implementation of unsupervised Part-of-Speech (POS) tagging using SVD and clustering techniques, based on the paper "SVD and Clustering for Unsupervised POS Tagging".

## Overview

This project implements an unsupervised approach to POS tagging using Singular Value Decomposition (SVD) and clustering techniques. The implementation uses the Penn Treebank corpus and achieves competitive results compared to other unsupervised methods.

## Key Features

- Two-pass SVD and clustering algorithm
- Custom weighted k-means clustering implementation
- Multiple evaluation metrics:
  - Many-to-One (M:1) Accuracy
  - One-to-One (1:1) Accuracy
  - Variation of Information (VI) Score
  - Adjusted Rand Index (ARI)

## Requirements

- Python 3.x
- NLTK
- NumPy
- scikit-learn
- SciPy

## Current Status
All work is in `fds_implementation_final.ipynb`. The `ptb.test/train/valid.txt` are unused owing to unavailability of propely tagged correct data. We had to resort to using NLTK's tagset and respective small corpus instead of the forty thousand word corpus planned earlier. 

**other_things** has a markdown-typed overview and screenshots of the work. 
