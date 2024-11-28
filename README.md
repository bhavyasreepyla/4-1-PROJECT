# 4-1-PROJECT
## Hybrid-Similarity-Model-for-Mitigating-the-Cold-Start-Problem-of-Collaborative-Filtering-in-Sparse-Data

### **Table of Contents**
1. [Introduction](#introduction)
2. [Objective](#objective)
3. [Project Workflow](#project-workflow)
4. [Installation and Setup](#installation-and-setup)
5. [Dataset Information](#dataset-information)
6. [Resources](#resources)

---

### **Introduction**
This repository implements a hybrid similarity model for collaborative filtering to improve recommendations in sparse data environments. By leveraging various models for item similarity and a novel approach for user similarity, the model enhances prediction accuracy for MovieLens-100k dataset.

---

### **Objective**
The objective of this project is to develop a robust collaborative filtering model that addresses the challenges of sparse data in recommendation systems. By combining Wasserstein distance-based item similarity and a unique user similarity calculation, the model aims to improve recommendation quality and accuracy

---

### **Project Workflow**


1. **Data Preparation**:  
   - Combine multiple training and testing folds into single unified datasets.  
   - Ensure the data is clean, structured, and ready for analysis.  

2. **Similarity Computation**:  
   - Compute user similarity using a mix of traditional, advanced, and hybrid models.   
   - Generate comprehensive similarity matrices for analysis.  

3. **Visualization**:  
   - Create heatmaps to visually represent user similarities and patterns.  
   - Leverage visual insights to validate and refine similarity computations.  

4. **Model Evaluation**:  
   - Evaluate the effectiveness of similarity models using metrics such as MAE, RMSE, and F1-score.  
   - Compare model performance across different datasets and scenarios to ensure accuracy and robustness.
  
---

### **Installation and Setup**

1. **Clone the Repository**
   ```bash
   git clone <repository_url>
   cd <repository_directory>
   ```
2. **Install Dependencies**
   Use the following commands to install required libraries:
   ```bash
   pip install numpy pandas scipy scikit-learn tqdm matplotlib
   ```
3. **Download Dataset**
   
   [https://grouplens.org/datasets/movielens/100k/](https://grouplens.org/datasets/movielens/100k/)

---

### **Dataset Information**

### The MovieLens 100k dataset contains:

1. *100,000* ratings (1-5) from *943* users on *1,682* movies.
2. Includes user demographics (age, gender, occupation, zip code) and movie genres (19 categories, multi-genre possible).
3. Collected between September 1997 and April 1998, with all users rating at least *20* movies.

For full details and citation guidelines, visit the GroupLens-website(https://files.grouplens.org/datasets/movielens/ml-100k-README.txt).

---
   
