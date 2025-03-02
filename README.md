# Image Colorization & Segmentation using VAE and U-Net

## 📌 Introduction
This project explores two fundamental computer vision tasks:

- **Image Colorization** using **Variational Autoencoder (VAE)**.
- **Image Segmentation** using **U-Net**.

These techniques are widely used in applications like medical imaging, photo restoration, and autonomous driving.

---

## 🎯 Project Goals
This project aims to:
1. Implement **Variational Autoencoders (VAE)** for image colorization.
2. Apply the **U-Net architecture** for image segmentation.
3. Learn **image preprocessing techniques**, including data augmentation.
4. Analyze model performance using relevant metrics.
5. Explore how **latent space representations** affect output quality.

---

## 📂 Dataset
The project utilizes a dataset of grayscale images for colorization and labeled images for segmentation.
Dataset : https://drive.google.com/drive/folders/1KeJbfUykGnPlz0q08_b1IjtW8OxkPdQ9?usp=sharing
یش

### 🔹 Data Processing Steps:
- Load and preprocess images.
- Apply transformations such as normalization and augmentation.
- Prepare data for deep learning models.

---

## 🛠️ Requirements & Installation
This project uses **Google Colab** for execution. Install the required dependencies before running the notebook:

```bash
pip install pytorch_lightning seaborn
```

Additionally, mount Google Drive to access datasets:

```python
from google.colab import drive
drive.mount('/content/drive/')
```

---

## 🚀 How to Run
1. Open the Jupyter Notebook in Google Colab.
2. Run the installation and dataset preparation cells.
3. Train the **VAE model** for image colorization.
4. Train the **U-Net model** for image segmentation.
5. Evaluate model performance.

---

## 📊 Results
- The **VAE model** generates colorized images with varying levels of realism.
- The **U-Net model** achieves **high segmentation accuracy**, effectively learning pixel-wise classification.
- Performance analysis includes **loss curves**, **sample outputs**, and **evaluation metrics**.

---

## 🤖 Technologies Used
- **Python, PyTorch, PyTorch Lightning**
- **Deep Learning (VAE, U-Net)**
- **Computer Vision (OpenCV, PIL)**
- **Data Processing (NumPy, Pandas, Seaborn)**

---

## 📬 Contact
For any questions or suggestions, feel free to reach out!
email : mobina.kochaknia01@sharif.edu
ن
ئخ

---

💡 **Tip:** Upload this repository to GitHub for better visibility. You can also add visualizations of results using images/screenshots.

