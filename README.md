# KOA-SEVERITY-CLASSIFICATION


This repository contains the final project for the Complex Data Mining course at SPPU.

Knee Osteoarthritis
Knee osteoarthritis is a pathology that occurs due to wear on the cartilage that protects the bones in this region from friction and impacts.

Medical procedures such as X-rays or magnetic resonance imaging (MRI) are used to identify this pathology. These imaging techniques help assess the loss of joint spacing, indicating the severity of the disease.

Classification of Osteoarthritis Severity
The severity of osteoarthritis is classified into five levels based on the Kellgren and Lawrence (KL) score. The greater the severity, the smaller the spacing of the joint.

KL Score Classification:
Grade 0: Healthy
Grade 1: Doubtful
Grade 2: Minimal
Grade 3: Moderate
Grade 4: Severe
The following image illustrates the different levels from the Knee Osteoarthritis Dataset with Severity Grading:

KL Score Grading

Project Overview
This project utilizes deep convolutional neural networks (CNNs) to analyze X-ray images and classify the severity of knee osteoarthritis.

Features:
Dataset: Knee Osteoarthritis Dataset with Severity Grading
Model: Deep CNN for automated classification
Goal: Assist in the early diagnosis and grading of knee osteoarthritis using AI
Directory Structure
Knee OA/
├── app.py
├── app/
│   └── img/
└── assets/
Installation
To set up the project, clone this repository and install the necessary dependencies:

git clone https://github.com/yourusername/knee-osteoarthritis-analysis.git
cd knee-osteoarthritis-analysis
pip install -r requirements.txt
Usage
Run the application:

python app.py
For inference on new images:

python app.py --image app/img/sample_image.png
License
This project is licensed under the MIT License.

Purpose
The purpose of this project is to correctly classify the severity of osteoarthritis based on X-ray images.
