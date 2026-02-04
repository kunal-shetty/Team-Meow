# Chest X-ray Disease Prediction Project Overview

This project focuses on building a machine learning pipeline to analyze chest X-ray images and predict possible diseases based on visual patterns present in the scans.
The model was trained **without using any pre-trained networks**, emphasizing core ML and computer vision fundamentals.

In addition to prediction, the system also generates **visual explanations (heatmaps)** to highlight the regions of the X-ray that influenced the model’s decision.

## 🧠 Problem Statement

Given a chest X-ray image, predict the presence of a disease and provide a confidence score along with visual interpretability.

## ⚙️ Tech Stack

* Python
* Google Colab
* NumPy
* Pandas
* OpenCV
* Matplotlib
* Scikit-learn / TensorFlow / Keras (as applicable)

## 📂 Dataset

* The dataset consists of **Chest X-ray images**
* Dataset is stored in **Google Drive**
* Accessed directly in Google Colab using Drive mounting

> Note: Due to dataset size and privacy considerations, the dataset is **not included** in this repository.

## 🚀 How to Run the Project (Google Colab)

1. Open the notebook in **Google Colab**
2. Mount Google Drive:

   ```python
   from google.colab import drive
   drive.mount('/content/drive')
   ```
3. Update the dataset path in the notebook:

   ```python
   data_path = "/content/drive/MyDrive/<your_dataset_folder>"
   ```
   Dataset drive link: https://drive.google.com/drive/folders/10eJVzzZTU8RvTB_FKh4tJqMlPVVZhhL_?usp=drive_link
   
5. Run all cells sequentially to:

   * Preprocess images
   * Train the model
   * Evaluate performance
   * Generate predictions and heatmaps

## 🔍 Model Pipeline

* Image preprocessing and normalization
* Feature extraction
* Model training from scratch
* Prediction with confidence scores
* Heatmap generation for visual interpretability

## 📊 Output

* Disease prediction label
* Prediction confidence
* Heatmap overlay highlighting affected regions in the chest X-ray

## 🤝 Team

* **Kunal**
* **Harsh Aair**

## 🏆 Hackathon Context

This project was developed during the **Techतत्व Hackathon**, where:

* A large dataset was provided on the spot
* Pre-trained models were strictly prohibited
* The entire solution had to be built within **8 hours**

## 📈 Future Improvements

* Improve model accuracy with better feature extraction
* Extend to multi-disease classification
* Add web-based UI for real-time predictions
* Integrate explainability techniques like Grad-CAM

## 📬 Contact

Feel free to connect on LinkedIn or explore the repository for further details.


