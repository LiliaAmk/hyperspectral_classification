#  Hyperspectral Image Classification

This project focuses on classifying hyperspectral images using deep learning techniques. Hyperspectral imaging provides rich spectral information across hundreds of bands, allowing precise land cover classification, especially in agricultural and urban applications.

##  Project Overview

- **Task:** Pixel-wise classification of hyperspectral images
- **Dataset:** Hyperspectral cube (e.g., Indian Pines, PaviaU)
- **Input:** 3D image cube (Height × Width × Bands)
- **Output:** Class label for each pixel
- **Goal:** Achieve high accuracy by leveraging spatial and spectral features

##  Notebook Highlights

1. **Data Loading**
   - Load hyperspectral data and ground-truth labels
   - Visualize band-wise and RGB-composite images

2. **Preprocessing**
   - Normalize spectral bands
   - Extract patches around pixels for context (optional)
   - Split into train/test/val sets

3. **Model**
   - Deep learning models such as CNN or 3D CNN
   - Optional: Traditional classifiers like SVM, Random Forest

4. **Training**
   - Cross-entropy loss, accuracy, and class-wise evaluation
   - Optional: Early stopping, learning rate scheduling

5. **Evaluation**
   - Overall accuracy (OA), average accuracy (AA), Kappa coefficient
   - Confusion matrix and classification map visualization

##  Dependencies

- Python 3.x
- NumPy, SciPy, Matplotlib
- TensorFlow or PyTorch
- Scikit-learn
- Spectral Python (`pip install spectral`)

##  Files

- `hyperspectral_classification.ipynb`: Main training and evaluation notebook
- `data/`: Contains hyperspectral images and labels (optional)
- `results/`: Classification outputs and maps

##  References

- [Indian Pines Dataset (Purdue University)](https://www.ehu.eus/ccwintco/index.php/Hyperspectral_Remote_Sensing_Scenes)
- [Spectral Python Library](https://www.spectralpython.net/)
