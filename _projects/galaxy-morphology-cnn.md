---
layout: page
title: "Galaxy Morphology Classification with CNNs"
description: "Final-year project applying convolutional neural networks to galaxy morphology classification using SDSS, Galaxy Zoo 2, and small ground-based telescope data."
img:
importance: 1
category: research
related_publications: false
---

## Overview

This project is my final-year research project for the BSc Physics with Astronomy & Space Science at University College Dublin.

The aim is to investigate whether convolutional neural networks trained on large astronomical imaging datasets can classify galaxy morphology in smaller ground-based telescope observations. The project combines astronomical data analysis, supervised machine learning, image preprocessing, and model evaluation.

## Scientific motivation

Galaxy morphology is an important observable in extragalactic astronomy because it traces galaxy structure, formation history, and evolutionary processes. Large surveys such as SDSS, together with human classifications from Galaxy Zoo 2, provide a valuable training set for supervised machine learning models.

A key challenge is whether models trained on survey-quality images can generalise to smaller ground-based telescope data, where images may have different resolution, depth, noise properties, and observing conditions.

## Data

The project uses:

- SDSS imaging data.
- Galaxy Zoo 2 morphology labels.
- Small ground-based telescope observations from Calar Alto-style imaging.
- Matched catalogues and image cutout manifests for reproducible training and evaluation.

## Methods

The project includes:

- Querying and curating galaxy morphology labels.
- Downloading and organising astronomical image cutouts.
- Preprocessing FITS/image data for machine learning.
- Training convolutional neural networks for binary and multi-class morphology classification.
- Evaluating model performance on SDSS test data and external small-telescope observations.
- Analysing prediction confidence, classification errors, and possible domain-shift effects.

## Tools and technologies

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- SciPy
- scikit-learn
- AstroPy
- Photutils
- Matplotlib
- Jupyter
- Git / GitHub
- Google Colab

## Skills demonstrated

- Machine learning for image classification.
- Astronomical data analysis.
- Scientific Python programming.
- Data preprocessing and model evaluation.
- Reproducible project organisation.
- Working with real observational datasets.
- Communicating scientific and technical results.

## Supervisor

Supervisor: Dr Antonio Martin-Carrillo, University College Dublin.

## Status

Ongoing final-year project.
