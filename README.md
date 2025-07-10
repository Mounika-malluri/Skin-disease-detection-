# Skin Disease Detection 🩺✨

A machine learning model to analyze skin lesion images and classify them into various disease categories (e.g., melanoma, benign, etc.). Built with Python and TensorFlow/Keras to aid in early diagnosis support.

---

## 🧠 Problem Statement  
Skin cancer and related conditions can be hard to diagnose visually. This project aims to leverage deep learning to assist dermatologists by providing an automated classification system for dermoscopic images.

---

## 🛠 Technologies Used  
- Python 3.x  
- TensorFlow & Keras  
- OpenCV / PIL for image preprocessing  
- NumPy, Pandas  
- Matplotlib / Seaborn for visualizations  
- Jupyter Notebook


```
Skin-disease-detection/
├── README.md
├── requirements.txt
├── src/
│   ├── preprocess.py
│   └── train_model.py
├── data/
├── notebooks/
├── models/
├── results/
```
---

## ▶️ Installation & Setup

```bash
git clone https://github.com/Mounika-malluri/Skin-disease-detection
cd Skin-disease-detection
pip install -r requirements.txt
```

---

## 🧪 Results

| Metric             | Score |
|--------------------|-------|
| Accuracy           | 88%   |
| Precision / Recall | Shown in confusion matrix (in notebooks) |

---

## 🚀 Usage Example

```python
from src.preprocess import preprocess_image
from tensorflow.keras.models import load_model

model = load_model('models/skin_model.h5')
img = preprocess_image('your_image.jpg')
pred = model.predict(img)
print(pred)
```

---

## 📈 Future Improvements

- Try deeper models (ResNet, EfficientNet)
- Add data augmentation
- Build a web app with Streamlit
- Improve generalization with larger dataset

---

## 📌 License

This project is licensed under the MIT License.




