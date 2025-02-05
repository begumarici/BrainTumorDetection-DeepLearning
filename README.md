# 🧠 Brain Tumor Detection Using Deep Learning  

##  Overview

Brain tumors can be life-threatening, and early detection is crucial for effective treatment.  
This project applies **deep learning** techniques using **MRI scans** to classify brain tumors into four categories:  
- **Glioma**  
- **Meningioma**  
- **No Tumor**  
- **Pituitary**  

It utilizes **pre-trained Convolutional Neural Networks (CNNs)** to achieve high accuracy in tumor detection.

## Deep Learning Models and Performance

| Model        | Accuracy  |
|-------------|----------|
| **VGG19**      | **96.00%** |
| **ResNet50**   | 82.03%  |
| **ResNet101**  | 82.56%  |
| **InceptionV3**| 92.17%  |
| **DenseNet121**| 91.46%  |

## Key Features  

**Multiple CNN Architectures:** Evaluates and compares five deep learning models (VGG19, ResNet50, ResNet101, InceptionV3, DenseNet121) for tumor classification.
**Smart Training Optimization:** Uses early stopping to prevent overfitting and learning rate scheduling for better convergence.
**Comprehensive Evaluation:** Includes confusion matrices, accuracy graphs, and detailed performance metrics for model comparison. 

---

**For dataset details**, check:  
📄 **[`dataset_description.md`](./dataset_description.md)**  

---

### Dataset Setup  

This project uses the **Brain Tumor MRI Dataset** from Kaggle.  

#### **Steps to Use the Dataset:**  
1. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset).  
2. Extract it into the `data/` folder in your project directory.  
3. Ensure the folder structure looks like this:  

```/data/brain-tumor-mri-dataset/
├── Training/
│   ├── glioma/
│   ├── meningioma/
│   ├── notumor/
│   ├── pituitary/
├── Testing/
│   ├── glioma/
│   ├── meningioma/
│   ├── notumor/
│   ├── pituitary/
```## Contributors  

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/begumarici">
        <img src="https://github.com/begumarici.png" width="80" height="80"><br>
        <sub><b>Begüm Arıcı</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/aleynatunc">
        <img src="https://github.com/aleynatunc.png" width="80" height="80"><br>
        <sub><b>Aleyna Tunç</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/yasemin-torun">
        <img src="https://github.com/yasemin-torun.png" width="80" height="80"><br>
        <sub><b>Yasemin Torun</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/zeynepkrksl">
        <img src="https://github.com/zeynepkrksl.png" width="80" height="80"><br>
        <sub><b>Zeynep Karakaşlı</b></sub>
      </a>
    </td>
    
  </tr>
</table>
