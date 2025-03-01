
# **Single Image Super-Resolution using Deep Learning**  

**Enhancing low-resolution images using CNNs and GANs**  

Developed under the guidance of **Dr. Nirbhay Kumar Tagore**  

---

## **📌 Overview**  
This project implements **Single Image Super-Resolution (SISR) using Deep Learning**, improving image resolution and reducing analysis errors. It utilizes **Convolutional Neural Networks (CNNs) and Generative Adversarial Networks (GANs)** to upscale low-resolution images effectively.  

🔹 **Key Technologies:** Python, TensorFlow, Keras  
🔹 **Applications:** Medical Imaging, Satellite Imagery, Surveillance  

---

## **📊 Features**  
✔️ CNN & GAN-based Super-Resolution Model  
✔️ Improved image clarity & detail retention  
✔️ Achieves higher **PSNR (Peak Signal-to-Noise Ratio)** & **SSIM (Structural Similarity Index)** than traditional methods  
✔️ Trained on **high-quality datasets** like **DIV2K, Set14**  

---

## **📂 Datasets Used**  
- **DIV2K** – High-resolution images for super-resolution tasks  
- **Set5 & Set14** – Standard benchmarks for evaluating performance  

---

## **⚡ Installation & Setup**  

### **1️⃣ Clone the Repository**  
```bash
git clone https://github.com/ankurkr07/Image-Super-Resolution.git
cd Image-Super-Resolution
```

### **2️⃣ Install Dependencies**  
```bash
pip install -r requirements.txt
```

### **3️⃣ Run the Model on a Sample Image**  
```bash
python run_model.py --input images/low_res.jpg --output images/high_res.jpg
```

### **4️⃣ Train the Model (Optional, If You Want to Retrain)**  
```bash
python train.py --dataset DIV2K --epochs 50
```

### **5️⃣ Evaluate Model Performance**  
```bash
python evaluate.py --testset Set14
```

---

## **📈 Results**  
✅ **Improvement in image resolution** (Measured using PSNR & SSIM)  
✅ **Reduction in errors** in low-quality image analysis  
✅ Outperforms **bicubic interpolation** and traditional upscaling methods  

---

## **🛠️ Model Architecture**  
- **Generator:** A deep CNN-based upscaler  
- **Discriminator:** GAN-based adversarial training for high-detail generation  
- **Loss Functions:** Perceptual loss (MSE + VGG loss) for realistic enhancement  

---

## **🔗 References & Resources**  
- [TensorFlow Documentation](https://www.tensorflow.org/)  
- [DIV2K Dataset](https://data.vision.ee.ethz.ch/cvl/DIV2K/)  
- [Super-Resolution Research Papers](https://arxiv.org/abs/1609.04802)  

---
 
