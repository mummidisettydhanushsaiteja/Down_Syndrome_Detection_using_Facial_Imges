🧠 Deep learning tool for early diagnosis of Down Syndrome using facial images 👶📸. Combines VNL-Net (VGG16 + NMF + LGBM) and MobileNet+SVM for accurate, real-time, and non-invasive detection ✅. Optimized for mobile & edge deployment 📱⚡.

🧠 Down Syndrome Detection Using Facial Images

A Final Year Project focused on creating a non-invasive, AI-powered diagnostic tool for detecting Down Syndrome in children using deep learning and facial image analysis.

---

 📌 Overview

Early and accurate diagnosis of Down Syndrome is crucial for effective medical intervention. This project proposes a novel, real-time diagnostic system leveraging:

- 🧬 VNL-Net: Combines VGG16, Non-Negative Matrix Factorization (NMF), and Light Gradient Boosting Machine (LGBM) for robust feature extraction.
- 🤖 MobileNet + SVM: Optimized for lightweight, mobile-friendly diagnosis.

> 🔍 Our models classify facial images to distinguish between Down Syndrome and healthy children, providing an efficient, scalable, and cost-effective solution.

---

 🧪 Key Features

✅ Non-invasive diagnosis  
✅ High accuracy with hybrid models  
✅ Real-time performance on edge/mobile devices  
✅ Modular design with Transfer Learning  
✅ Evaluated with K-Fold Cross Validation  

---

 📂 Project Structure


Down\_Syndrome\_Detection/
├── dataset/              # Facial image data
├── model/                # Trained models
├── notebooks/            # Jupyter notebooks for training/testing
├── static/               # CSS/JS if web interface is used
├── templates/            # HTML files (Flask/Streamlit)
├── app.py                # Main web app file
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation

---

 ⚙️ Technologies Used

- 🐍 Python 3.8+
- 📚 TensorFlow, Keras, Scikit-Learn
- 📷 OpenCV, NumPy, Pandas
- 🌐 Flask (Web Interface)
- 📱 MobileNet, VGG16
- 🔍 SVM, LGBM, NMF

---

 🚀 How to Run the Project

1. Clone the repository:
   
   git clone https://github.com/YOUR-USERNAME/Down_Syndrome_Detection.git
   cd Down_Syndrome_Detection

2. Install dependencies:

   pip install -r requirements.txt

4. Run the app:

   python app.py

5. Open your browser and go to http://localhost:5000

---

 📊 Results

 ✅ Achieved high classification accuracy
 ✅ Lightweight model for mobile deployment
 ✅ Outperformed traditional diagnostic methods in terms of speed and accessibility

---

 🏥 Real-World Applications

 Pediatric diagnostic support
 Telemedicine and remote screening
 Educational tools for medical training
 Scalable public health screening initiatives

---

 📚 Learning Outcomes

 Applied advanced transfer learning for medical imaging
 Integrated hybrid models for enhanced classification
 Implemented dynamic model selection and adaptive learning
 Validated models using K-Fold cross-validation

---
