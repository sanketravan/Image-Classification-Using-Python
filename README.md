# 🖼️ Image Classification Using Python

A modern Image Classification web application built with **Python, PyTorch, and Streamlit** that classifies uploaded images using a pre-trained **ResNet-101** deep learning model trained on the ImageNet dataset. The application provides fast and accurate predictions through a clean and interactive web interface.

---

## 🚀 Features

- Classifies uploaded images into ImageNet categories
- Uses a pre-trained ResNet-101 deep learning model
- Displays top predictions with confidence scores
- Simple and interactive Streamlit web interface
- Real-time image inference
- Lightweight and easy to run locally

---

## 🛠️ Tech Stack

- Python
- PyTorch
- TorchVision
- Streamlit
- Pillow

---

## 📂 Project Structure

```
Image-Classification-Using-Python/
│── streamlit_ui.py
│── requirements.txt
│── imagenet_classes.txt
│── README.md
│── Dockerfile
│── .gitignore
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/your-username/Image-Classification-Using-Python.git
cd Image-Classification-Using-Python
```

### Create a Virtual Environment

```bash
python -m venv venv
```

Activate the environment

**Windows**

```bash
venv\Scripts\activate
```

**Linux / macOS**

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
streamlit run streamlit_ui.py
```

Then open your browser and visit:

```
http://localhost:8501
```

---

## 📖 How It Works

1. Upload an image in JPG format.
2. The image is preprocessed using TorchVision transforms.
3. A pre-trained ResNet-101 model performs inference.
4. The application predicts the image category.
5. Top predictions with confidence scores are displayed.

---

## 📊 Model

- Architecture: **ResNet-101**
- Framework: PyTorch
- Dataset: ImageNet
- Classes: 1000 object categories

---

## 📸 Demo

Upload an image and instantly receive the top predicted classes along with their confidence scores.

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

## 📄 License

This project is intended for educational and learning purposes.

---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub!
