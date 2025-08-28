
# DimRed-Learn: Hands-on Dimensionality Reduction with PCA & LDA  

This repository contains a simple, guided project designed for students to **learn and practice dimensionality reduction techniques** in machine learning using **PCA (Principal Component Analysis)** and **LDA (Linear Discriminant Analysis)**.  

## 📌 Project Overview
The project is structured as a series of exercises to help understand:
1. **Data preprocessing & visualization**
   - Load dataset, pick sample images from each class  
   - Add Gaussian noise and visualize noisy vs. clean images  

2. **PCA from scratch**
   - Implement PCA without using ML libraries  
   - Compute explained variance ratio  
   - Determine the number of components needed to preserve ≥90% variance  

3. **PCA with scikit-learn**
   - Reduce data to 2 principal components  
   - Visualize in 2D scatter plots (color-coded by class)  

4. **Image reconstruction using PCA**
   - Project noisy images into PCA subspace  
   - Reconstruct and compare clean, noisy, and reconstructed images  

5. **LDA with scikit-learn**
   - Reduce data to 2 discriminant components  
   - Visualize results and compare with PCA  

6. **Class separability analysis**
   - Compute Fisher’s criterion: `trace(Sw⁻¹ Sb)`  
   - Analyze effect of number of features on separability  
   - Identify optimal number of features  

## 🛠 Requirements
- Python 3.x  
- numpy, matplotlib, scikit-learn  

## 🚀 How to Run
Clone the repo and run the Jupyter Notebook:  
```bash
git clone https://github.com/your-username/DimRed-Learn.git
cd DimRed-Learn
jupyter notebook
