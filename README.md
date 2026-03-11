# 🔢 CNN Digit Recognition App

> A Streamlit web application for **real-time handwritten digit prediction** using a PyTorch Convolutional Neural Network trained on the MNIST dataset.

## 🚀 Live Demo
> *(Deploy on [Streamlit Cloud](https://streamlit.io/cloud) — it's free! Add your link here)*

## 📸 Screenshot
> *(Add a screenshot of your app here)*

## 🧠 How It Works
1. User draws a digit on a canvas in the browser
2. The image is preprocessed and passed to a PyTorch CNN model
3. The model predicts the digit with confidence scores

## 🛠️ Tech Stack
- **Model**: PyTorch CNN trained on MNIST (99%+ accuracy)
- **Frontend**: Streamlit
- **Deployment**: Streamlit Cloud

## ⚙️ Run Locally

```bash
git clone https://github.com/Mdshafeeulla/cnn-digit-recognition-app
cd cnn-digit-recognition-app
pip install -r requirements.txt
streamlit run app.py
```

## 📊 Model Architecture
- Conv2D → ReLU → MaxPool
- Conv2D → ReLU → MaxPool
- Fully Connected → Softmax

## 📈 Results
- Training Accuracy: ~99.2%
- Test Accuracy: ~99.1%

---
⭐ Star this repo if you found it useful!
