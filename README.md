# Accent, Gender, and Age Prediction Based on Audio

This project is part of the **MATH UN2015 Linear Algebra & Probability** course for the **Fall 2024 semester** at **Columbia University**.

## Project Overview
The goal of this project is to develop a predictive model that classifies speaker attributes, specifically **accent**, **gender**, and **age**, based on audio data. The model leverages feature extraction techniques to capture relevant characteristics of the speaker's voice that contribute to these classifications.

## Methodology
Key features such as **pitch**, **words per second**, and **tempo** will be extracted from the audio files using linear algebra-based algorithms. These features will then be used to train a **Logistic Regression** model for classification. 


## Model
The project will train a **Logistic Regression** model using the extracted features to predict the target attributes: **gender**, **age**, and **accent**.

## Deliverables
- Audio file classification based on accent, gender, and age.
- Visualizations of intermediate steps, such as feature distribution and PCA results, to help interpret the model's performance.


## Installation
1. Clone the repository:  
   `git clone <repository_url>`
   
2. Create the anaconda environment with:  
   `conda env create -f environment.yml`
   
3. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/mozillaorg/common-voice) and replace the common-voice directory


## Usage
Run the 'un2015.ipynb'
Check the report 'final_report.pdf'
