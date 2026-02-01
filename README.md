[Open in Colab](https://colab.research.google.com/drive/1jgDBripN8bLtnloKipJzZIATH0I2kC8l?usp=sharing)

# Explainable Chest X-ray Pneumonia Detection

This repository contains a small research prototype developed to explore explainable AI for chest X-ray analysis.

## Overview
- Task: Pneumonia classification from chest X-ray images
- Model: ResNet18 (pretrained)
- Explainability: Grad-CAM visual explanations
- Goal: Improve transparency and clinical interpretability

## Input and Output
**Input:**  
- Single chest X-ray image (frontal view)

**Output:**  
- Binary classification: *Normal* or *Pneumonia*  
- Grad-CAM heatmap highlighting lung regions that most influenced the model’s prediction  
- Textual, knowledge-guided explanation generated using a lightweight LLM

## Motivation
Rather than focusing only on accuracy, this prototype explores how visual explanations can help align model predictions with clinically meaningful regions in medical images.

## Methods
- Chest X-ray dataset (binary classification: Normal vs Pneumonia)
- Grad-CAM applied to highlight lung regions influencing the model’s decision
- Visual inspection of explanations for clinical relevance

## Notes
This is a preliminary prototype developed for research exploration and discussion purposes. Future work may extend this to multimodal learning and knowledge-guided reasoning.

## Usage
Open the notebook `gradcam_chestxray.ipynb` to reproduce the experiment.
