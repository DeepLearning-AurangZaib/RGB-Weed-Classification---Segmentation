RGB Weed Classification and Segmentation using Deep Learning
This repository contains code and resources for the paper:

"Comparative Evaluation of Lightweight Deep Learning Models for Weed Classification and Segmentation Using SAM-Assisted Annotation"

📌 Overview
This work evaluates deep learning models across:

Classification (MobileNetV3)
Instance Segmentation (YOLOv11)
Semantic Segmentation (DeepLabV3+, SegFormer)

📁 Repository Structure
Dataset/ → Images, Masks, Labels, Labels-Seg
notebooks/ → Jupyter notebooks
scripts/ → Preprocessing & conversion
results/ → Figures and tables

🚀 Models Used
23 lightweight CNN models for Classsification, including:
•	MobileNet family (V1, V2, V3) 
•	EfficientNet (B0–B4) and EfficientNetV2 variants (Tan and Le 2021)
•	DenseNet (121, 169, 201) (Huang et al. 2017)
•	ResNet (18, 50, 50V2) (He et al. 2016)
•	Xception, InceptionV3, NASNetMobile (Zoph et al. 2018)

For Instance Segmentation
  YOLOv11
For Semantic Segmentation
  DeepLabV3+
  SegFormer-B0

📊 Datasets
Datatset contain Images, Masks, Labels, Labels-Seg of 4 weeds

Requirements
See requirements.txt

Usage
Run notebooks in /notebooks folder
