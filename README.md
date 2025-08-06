#  Custom CNN Image Classification

This project implements and compares three convolutional neural network (CNN) architectures for image classification:

- **Custom-built CNN** (from scratch)
- **VGG16** (transfer learning)
- **AlexNet** (transfer learning)

All models are implemented in **PyTorch** and trained on a dataset with **19 image classes**.

---

##  Project Structure

- `Untitled12.ipynb` – Jupyter Notebook containing the full implementation, training, evaluation, and prediction logic.
- `colab fix.pdf` – Visual report showing training progress, accuracy trends, and final outputs.

---

##  Dataset

- **Format:** [ImageFolder](https://drive.google.com/drive/folders/1P2D6z3SQsj4ngEDJt9LdBKn9ZRF5KqP4?usp=drive_link)  
- **Training samples:** 4,570 images  
- **Testing samples:** 1,131 images  
- **Number of classes:** 19  

---

##  Models Implemented

### 🔹 Custom CNN  
- Built from scratch using 4 convolutional blocks  
- **Test Accuracy:** 73.03%  

### 🔹 VGG16 (Transfer Learning)  
- Pretrained VGG16 with modified classifier layers  
- **Test Accuracy:** 90.72%  

### 🔹 AlexNet (Transfer Learning)  
- Pretrained AlexNet with customized output layer  
- **Test Accuracy:** 86.38%  

---

##  Technologies Used

- Python  
- PyTorch  
- torchvision  
- Google Colab  
- PIL  
- matplotlib  

---

##  Instructions to Run

1. Open `Untitled12.ipynb` in [Google Colab](https://colab.research.google.com/drive/1FC5xKG4SIhLydr8baxRKlhH-4T89MXrL#scrollTo=xLMUaAxoUEHg).  
2. Mount your dataset via Google Drive.  
3. Run all cells sequentially to train and evaluate the models.  
4. Modify the prediction cell to test with your own custom images.  

---
