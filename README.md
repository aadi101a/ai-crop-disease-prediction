# 🌱 AI Driven Crop Disease Prediction and Management System

This project uses **Deep Learning (CNN / Transfer Learning)** to predict crop diseases from leaf images and provide possible management strategies.  
It aims to help farmers and agricultural researchers quickly identify plant diseases and take timely action.  

---

## 🚀 Features
- Upload crop/leaf image and get instant disease prediction  
- Deep Learning based model trained on crop disease dataset  
- Supports multiple crops and diseases  
- Jupyter Notebooks for training & evaluation  
- Python scripts for prediction and automation  
- Extensible for adding new crops/diseases  

---

## 📂 Project Structure
├── dataset/ # Training & testing datasets (not uploaded to GitHub)
│ ├── train/ # Training images
│ ├── test/ # Testing images
│ └── labels/ # Labels/annotations (if available)
│
├── models/ # Saved trained models (e.g., .h5, .pt, .pth files)
│ └── crop_disease_model.h5
│
├── notebooks/ # Jupyter notebooks for experiments & EDA
│ └── crop_disease_training.ipynb
│
├── src/ # Source code scripts
│ ├── data_loader.py # Data loading & preprocessing
│ ├── model.py # DL model architecture (CNN/Transfer Learning)
│ ├── train.py # Training script
│ ├── evaluate.py # Model evaluation
│ └── predict.py # Predict disease from input image
│
├── requirements.txt # Python dependencies
├── .gitignore # Ignored files & folders
├── LICENSE # Project license
└── README.md # Documentation


> Note: Due to large size, **dataset** and **trained models** are not included in this repository.  

---

## ⚙️ Installation

1. Clone the repository  
   ```bash
   git clone https://github.com/aadi101a/crop-disease-prediction.git
   cd crop-disease-prediction

2. Create a virtual environment (optional but recommended)
     python -m venv venv
     source venv/bin/activate   # Linux/Mac
     venv\Scripts\activate      # Windows

3. Install dependencies
    pip install -r requirements.txt

🧑‍💻 Usage

*Training the Model
  python src/train.py

*Evaluating the Model
   python src/evaluate.py

*Predicting Crop Disease
   python src/predict.py --image path_to_leaf.jpg

📊 Dataset

*Publicly available crop disease datasets such as PlantVillage can be used.
*The dataset should be organized into train/ and test/ directories.

🔮 Future Enhancements

*Web App / Mobile App integration for farmers
*Multilingual disease management advice
*Integration with IoT sensors for real-time monitoring

🤝 Contributing

*Contributions are welcome!
*Feel free to fork the repo, create a new branch, and submit a pull request.

👨‍💻 Author

Name: Mohd Adeeb &
GitHub: aadi101a

📜 License

This project is licensed under the MIT License
