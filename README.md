# COVID-19 Detection on Chest X-ray
**Computer Vision Project 2021**  
- train CNN to classify Covid-19 vs. Viral Pneumonia vs. Normal (Healthy) from Chest X-Ray Images (kaggle dataset) 
- evaluate training results
- visualize classification with Grad-CAM and LIME

## Model Training and Evaluation

Folder Structure for model training:

MyDrive  
└── cvproject  
    ├── COVID-10 Radiography Database  
    │   ├── COVID-19  
    │   ├── NORMAL  
    │   └── Viral Pneumonia  
    └── training_results  

Run **cv_model_training.ipynb** to...
- create subfolder in *training_results* folder to store training results
- save trained model (.h5) to subfolder
- save training plots to subfolder
- save evaluation confusion matrix to subfolder
- save evaluation metrics and model architecture to results.txt file in **training_results**

## Visualization
Use notebooks in **visualization** folder to create visualization using Grad-CAM or LIME.

### Prerequisites
- trained model (.h5) to be loaded
- test dataset to be evaluated/visualized
