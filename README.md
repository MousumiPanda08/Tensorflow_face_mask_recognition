# Object Detection using TensorFlow (Face Mask Detection)

## About the Project

This project implements an object detection model using TensorFlow to detect faces and classify them based on mask usage. The model is trained on a Face Mask Detection dataset from Kaggle and can identify whether a person is wearing a mask, not wearing a mask, or wearing it incorrectly. Bounding box regression is used to accurately locate faces in images.

## Features

* Detects faces in images
* Classifies into: With Mask, Without Mask, Incorrect Mask
* Uses TensorFlow data pipeline and model training
* Visualizes predictions with bounding boxes
* Evaluates performance using metrics and IoU

## Tech Stack

TensorFlow
Python
NumPy
Matplotlib

## Dataset

Face Mask Detection Dataset (Kaggle)

## Project Workflow

* Data preprocessing and XML annotation parsing
* Bounding box handling (padding/truncation)
* Building TensorFlow data pipeline
* Model creation and training
* Evaluation and visualization of results

## What I Learned

* Object detection fundamentals
* Working with bounding boxes and annotations
* Building and training deep learning models in TensorFlow
* Evaluating model performance using IoU

## Challenges

* Handling variable number of bounding boxes
* Data preprocessing and annotation parsing
* Achieving good accuracy with limited dataset

## How to Run

1. Install dependencies
2. Run the notebook step by step
3. Train the model
4. Visualize predictions

