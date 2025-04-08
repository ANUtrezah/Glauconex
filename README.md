# GlaucoNex - Deep Learning-Based Glaucoma Detection System

GlaucoNex is a deep learning-based diagnostic system developed for automated **glaucoma detection** using **fundus images**. It leverages advanced **Convolutional Neural Networks (CNNs)** and **Cup-to-Disc Ratio (CDR)** calculation to classify eye conditions as **Normal**, **Suspicious**, or **Glaucomatous**.

---

## Features

- Classification of fundus images using CNNs (EfficientNet-b0, InceptionV3, etc.)
- CLAHE and Otsu's thresholding for contrast enhancement and segmentation
- CDR (Cup-to-Disc Ratio) based risk assessment
- Transfer learning for improved performance with limited data
- Visualization of optic disc and cup boundaries (Disc = Green, Cup = Blue)
- Graphical User Interface (GUI) for easy use

---

## Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- Scikit-learn
- MATLAB (for preprocessing and GUI design)
- Pre-trained models (EfficientNet, InceptionV3, MobileNet)

---

##  Project Structure

```plaintext
GlaucoNex/
│
├── preprocessing/       # Image resizing, CLAHE, thresholding
├── segmentation/        # Optic disc and cup segmentation
├── models/              # CNN architectures and training scripts
├── gui/                 # MATLAB GUI for CDR display and classification
├── dataset/             # Fundus images dataset
├── results/             # Output visualizations and CDR values
└── README.md            # Project description
