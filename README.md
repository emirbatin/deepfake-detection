# **DeepFake Detection Model**

📌 **High-Performance DeepFake Detection Using Advanced Spectral Analysis and Attention Mechanisms**  
📌 **Gelişmiş Spektral Analiz ve Dikkat Mekanizmaları ile Yüksek Performanslı DeepFake Tespiti**  

---

## **📖 Overview | Genel Bakış**
### **English**  
This repository contains an advanced DeepFake detection model that leverages a **ConvNeXt backbone**, **spectral analysis (FFT, DCT)**, and **attention mechanisms** to improve accuracy in detecting AI-generated fake images. The model is trained on the **140K Real and Fake Faces dataset** and optimized with **progressive training**, **Mixup augmentation**, and **gradient clipping** techniques.

### **Türkçe**  
Bu depo, **ConvNeXt omurgası**, **spektral analiz (FFT, DCT)** ve **dikkat mekanizmaları** kullanarak **AI tarafından üretilmiş sahte yüzleri tespit etmek** için geliştirilmiş bir DeepFake tespit modelini içermektedir. Model, **140K Gerçek ve Sahte Yüzler veri seti** ile eğitilmiş olup, **kademeli eğitim**, **Mixup veri artırma** ve **gradyan kırpma** teknikleriyle optimize edilmiştir.

---

## **🚀 Features | Özellikler**
✅ **ConvNeXt Backbone:** High-performance feature extraction for DeepFake detection.  
✅ **Spectral Analysis (FFT, DCT):** Extracts frequency-based features to identify fake images.  
✅ **Attention Mechanism:** Enhances feature representation for better classification.  
✅ **Progressive Training:** Gradually unfreezes layers to improve transfer learning.  
✅ **Mixup Data Augmentation:** Helps the model generalize better by mixing images.  
✅ **Advanced Evaluation Metrics:** Includes AUC-ROC, PR-AUC, confusion matrices, and misclassification analysis.  

✅ **ConvNeXt Omurgası:** DeepFake tespiti için yüksek performanslı özellik çıkarımı.  
✅ **Spektral Analiz (FFT, DCT):** Sahte görüntüler için frekans tabanlı özellikleri çıkarır.  
✅ **Dikkat Mekanizması:** Daha iyi sınıflandırma için özellik temsillerini gücülendirir.  
✅ **Kademeli Eğitim:** Transfer öğrenimini geliştirmek için katmanları kademeli olarak çözer.  
✅ **Mixup Veri Artırma:** Modelin genelleştirme yeteneğini artırmak için görüntülerı karıştırır.  
✅ **Gelişmiş Değerlendirme Metrikleri:** AUC-ROC, PR-AUC, karmaşıklık matrisi ve yanlış sınıflandırma analizi içerir.  

---

## **📂 Dataset | Veri Seti**
**📌 Dataset:** [140K Real and Fake Faces]([https://www.kaggle.com/datasets/x/140k-real-and-fake-faces](https://www.kaggle.com/datasets/xhlulu/140k-real-and-fake-faces))  
- **Train:** 5000 images (2500 real, 2500 fake)  
- **Validation:** 5000 images (2500 real, 2500 fake)  
- **Test:** 5000 images (2500 real, 2500 fake)  

**📌 Veri Seti:** [140K Gerçek ve Sahte Yüzler]([https://www.kaggle.com/datasets/x/140k-real-and-fake-faces](https://www.kaggle.com/datasets/xhlulu/140k-real-and-fake-faces))  
- **Eğitim:** 5000 görüntü (2500 gerçek, 2500 sahte)  
- **Doğrulama:** 5000 görüntü (2500 gerçek, 2500 sahte)  
- **Test:** 5000 görüntü (2500 gerçek, 2500 sahte)  

---

## **🛠 Installation | Kurulum**
```bash
git clone https://github.com/emirbatin/deepfakedetection.git
cd deepfake-detection
pip install -r requirements.txt
```

---

## **🚀 Usage | Kullanım**
### **Training | Model Eğitimi**
```bash
python train.py --epochs 15 --batch_size 32 --learning_rate 0.0001
```

### **Testing | Modeli Test Etme**
```bash
python test.py --model_path best_model.pth --image_path example.jpg
```

---

## **🔍 Results | Sonuçlar**
### **📊 Confusion Matrix | Karmaşıklık Matrisi**
![Confusion Matrix](confusion_matrix.png)

### **📉 Training & Validation Loss | Eğitim & Doğrulama Kayıpları**
![Training Metrics](training_metrics.png)

---

## **📑 Model Performance | Model Performansı**
| Metric | Value |
|--------|------|
| **Test Accuracy** | **87.94%** |
| **ROC AUC Score** | **94.76%** |
| **PR AUC Score** | **94.66%** |
| **Best F1 Score** | **88.27% (Threshold: 0.4743)** |

---

## **📜 Citation | Atıf**
If you use this model, please cite:
```
@article{coming soon,
  title={High-Performance DeepFake Detection Using Advanced Spectral Analysis and Attention Mechanisms},
  author={Emir Batın Karaoglan},
  year={2025}
}
```

---

## **📬 Contact | İletişim** 
- **Email:** batin@cretique.net
- **LinkedIn:** [LinkedIn](https://linkedin.com/in/emirbatin)  

