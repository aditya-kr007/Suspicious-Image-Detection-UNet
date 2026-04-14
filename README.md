# 🔍 Suspicious Image Detection using Deep Learning (UNet)

This project implements a **Suspicious Image Detection System** using a **UNet-based deep learning segmentation model**. The system detects camouflaged or hidden objects in images by generating segmentation masks, detecting contours, and drawing bounding boxes around suspicious regions.

The model supports both **image upload** and **webcam input**, making it suitable for surveillance, monitoring, and security applications.

---

# 📌 Project Overview

Camouflaged objects are difficult to detect because they blend into their surroundings. Traditional classification models can only label images but cannot locate hidden objects.

This project uses **UNet segmentation**, which performs **pixel-level detection**, allowing the system to detect the exact location of suspicious objects.

---

# ✨ Features

- UNet-based deep learning segmentation model  
- Detects camouflaged or hidden objects  
- Generates probability maps  
- Converts predictions into binary masks  
- Uses contour detection to locate objects  
- Draws bounding boxes around detected regions  
- Supports image upload input  
- Supports webcam-based detection  
- Pixel-level object detection  
- High accuracy performance

---

# 🧠 How the Project Works

The system follows these steps:

```

Input Image (Upload / Webcam)
↓
Image Preprocessing
(Resize to 224×224 pixels)
↓
UNet Model Prediction
↓
Probability Mask Generation
↓
Binary Mask Creation
↓
Contour Detection
↓
Bounding Box Drawing
↓
Final Output Image

```

---

# 🏗 Model Architecture

The project uses the **UNet architecture**, which consists of:

- Encoder (Feature Extraction)
- Decoder (Image Reconstruction)
- Skip Connections (Detail Preservation)

UNet is ideal for segmentation tasks because it detects objects at the **pixel level**, making it suitable for camouflaged object detection.

---

# 📂 Dataset Used

**Dataset Name:** Adaptive Camouflaged Dataset (ACD1K)

**Dataset Details:**

- Total Images: 8000  
- Image Type: Camouflaged Objects  
- Mask Type: Binary Segmentation Masks  
- Input Size: 224 × 224 pixels  

The dataset contains images where objects are hidden within complex backgrounds.

---

# ⚙️ Technologies Used

- Python  
- TensorFlow / Keras  
- OpenCV  
- NumPy  
- Matplotlib  
- PIL (Python Imaging Library)  
- Google Colab  
- MacBook M1  

---

# 📊 Model Performance

| Parameter | Value |
|----------|--------|
| Training Accuracy | 95% |
| Validation Accuracy | 97% |
| Epochs | 50 |
| Batch Size | 16 |
| Optimizer | Adam |
| Input Size | 224 × 224 |

---

# 📸 Sample Outputs

The system generates:

- Probability Maps  
- Binary Masks  
- Overlay Visualizations  
- Bounding Box Detection  

Example output:

- Suspicious objects detected
- Bounding boxes drawn
- Multiple objects identified

---

# 📁 Project Structure

```

Suspicious-Image-Detection-Using-UNet/

│── dataset/
│    ├── images/
│    ├── masks/
│
│── model/
│    ├── Camouflaged_UNET_final.keras
│
│── notebooks/
│    ├── training.ipynb
│    ├── prediction.ipynb
│
│── outputs/
│    ├── results_images/
│
│── README.md
│── requirements.txt

```

---

# ▶️ Installation

Clone the repository:

```

git clone [https://github.com/your-username/Suspicious-Image-Detection-Using-UNet.git](https://github.com/your-username/Suspicious-Image-Detection-Using-UNet.git)
cd Suspicious-Image-Detection-Using-UNet

```

Install dependencies:

```

pip install -r requirements.txt

```

---

# ▶️ Usage

Run prediction script:

```

python predict.py

```

OR open Jupyter Notebook:

```

jupyter notebook

```

Then run:

```

prediction.ipynb

```

Upload image or use webcam for detection.

---

# 🎯 Applications

- Security Surveillance Systems  
- Suspicious Object Detection  
- Military Camouflage Detection  
- Wildlife Monitoring  
- Image Analysis Systems  

---

# 🚀 Future Improvements

- Real-time video detection  
- Mobile deployment  
- Improved detection accuracy  
- Use of advanced segmentation models  
- Cloud-based deployment  

---

# 👨‍🎓 Author

**Name:** Aditya Kumar  
**Registration No:** 20223016  
**Department:** Computer Science and Engineering  
**Institute:** Motilal Nehru National Institute of Technology (MNNIT), Prayagraj  

---

# 📜 License

This project is developed for academic and educational purposes.
```

---
