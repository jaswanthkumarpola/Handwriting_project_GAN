z# 🖊️ Handwriting Generator using GAN (PyTorch)

## 📌 Overview
This project implements a **Generative Adversarial Network (GAN)** in PyTorch to generate synthetic handwriting images.  
It trains a Generator and a Discriminator in an adversarial setup, producing realistic handwritten digits/letters after sufficient training.

---

## 🚀 Features
- GAN implemented in **PyTorch**
- Configurable latent dimension, learning rate, and training parameters
- Generates new handwriting images from random noise
- Visualization of generated samples during training
- Jupyter Notebook workflow for easy experimentation

---

## 🛠️ Tech Stack
- Python 🐍
- [PyTorch](https://pytorch.org/)
- NumPy
- Matplotlib
- Torchvision

---

## ⚙️ Installation
Clone the repository and install dependencies:

" git clone https://github.com/<your-username>/Handwriting_GAN.git "
cd Handwriting_GAN
pip install -r requirements.txt

1.▶️ Usage
- jupyter notebook Hand_writing_Generator.ipynb

2.Run all cells to:

- Load the dataset
- Train the GAN
- Generate new handwriting images

3.Adjust parameters (like latent_dim, epochs, batch_size) inside the notebook as needed.

4.Project Structure
           Handwriting_GAN/
│── Hand_writing_Generator.ipynb   # Main notebook
│── requirements.txt               # Dependencies
│── README.md                      # Documentation
│── outputs/                       # Generated images (after training)




📊 Results
After training for ~100 epochs, the Generator produces handwriting-like images:


👨‍💻 Author

Jaswanth Kuamr Pola - github.com/jaswanthkumarpola













