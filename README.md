# 🚦 Traffic Sign Recognition

A CNN-based Traffic Sign Recognition system built using **TensorFlow/Keras**. This project focuses on accurate classification of traffic signs using the **GTSRB dataset**, following clean repository structure and best practices.

---

## 📌 Project Overview

- **Goal:** Classify traffic signs using a Convolutional Neural Network (CNN)
- **Dataset:** GTSRB (German Traffic Sign Recognition Benchmark)
- **Frameworks:** TensorFlow, Keras
- **Language:** Python 3.7+
- **Use Case:** Academic projects, learning computer vision, deep learning demos

---

## 🎯 Prerequisites

Make sure you have the following installed:

- Git → [https://git-scm.com/downloads](https://git-scm.com/downloads)
- GitHub account → [https://github.com/join](https://github.com/join)
- Python 3.7 or higher → [https://www.python.org/downloads/](https://www.python.org/downloads/)
- Traffic sign dataset (GTSRB)

---

## 📂 Project Structure

```text
traffic-sign-recognition/
├── data/
│   ├── raw/
│   │   └── .gitkeep
│   └── processed/
│       └── .gitkeep
├── models/
│   └── .gitkeep
├── notebooks/
│   └── .gitkeep
├── src/
│   ├── __init__.py
│   └── traffic_sign_recognition.py
├── results/
│   └── .gitkeep
├── docs/
|
├── requirements.txt
├── .gitignore
├── LICENSE
└── README.md
```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/traffic-sign-recognition.git
cd traffic-sign-recognition
```

### 2️⃣ Create Virtual Environment (Recommended)

```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\\Scripts\\activate     # Windows
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 📊 Dataset Setup

### Option 1: External Download (Recommended)

Download the GTSRB dataset from:

- Kaggle: [https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign](https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign)

Extract the dataset into:

```text
data/raw/
```

### Option 2: Git LFS (For Large Files)

```bash
git lfs install
git lfs track "*.h5"
git lfs track "data/raw"

git add .gitattributes
git commit -m "Configure Git LFS"
```

---

## 🧠 Model Details

- **Architecture:** Convolutional Neural Network (CNN)
- **Input:** Traffic sign images
- **Classes:** 43
- **Optimizer:** Adam
- **Loss Function:** Categorical Crossentropy
- **Accuracy:** \~95% on test data

---

## ▶️ Run the Project

```bash
python src/traffic_sign_recognition.py
```

Make sure the dataset path inside the script matches your local setup.

---

## 📈 Results

- Test Accuracy: **\~95%**
- Training Time: \~15 minutes (15 epochs)
- Outputs:
  - Accuracy & loss plots
  - Confusion matrix
  - Saved trained model (optional)

---

## 📄 Documentation

All documentation files are stored in the `docs/` folder.

- **report.pdf** – Full project report
- **presentation.pptx** – Presentation slides

---

## 🚀 Release

Create your first release:

```bash
git tag -a v1.0.0 -m "Initial release"
git push origin v1.0.0
```

Then publish the release from GitHub → **Releases** section.

---

## 🛠 Troubleshooting

### Git Push Authentication Error

Use a Personal Access Token (PAT):

GitHub → Settings → Developer settings → Personal access tokens

### Large File Rejected

```bash
git rm --cached my_model.h5
echo "my_model.h5" >> .gitignore
git commit -m "Remove large model file"
git push
```

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 👤 Author

**Your Name**\
GitHub: [https://github.com/SAQIB821](https://github.com/SAQIB821)\
Email: **saqib12841284\@gmail.com**

---

## ⭐ Final Notes

- Star ⭐ the repository if you find it useful
- Fork it, improve it, and build on top of it
- Perfect for university projects and learning CNNs

---

Happy coding 🚀

