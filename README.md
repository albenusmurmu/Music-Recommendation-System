# 🎵 Music Recommendation System — Decision Tree

A simple **Machine Learning project** that predicts a user's preferred music genre based on basic user information such as **age and gender** using a **Decision Tree Classifier**.

---

## 📌 Project Overview

This project demonstrates how a **Decision Tree Classification algorithm** can learn patterns from user data and predict a suitable music genre.

The project also generates a `.dot` file containing the structure of the trained Decision Tree and uses **Graphviz** to visualize the tree.

### 🎯 Objective

Build a basic music recommendation model that predicts genres such as:

- 🎸 Acoustic
- 🎼 Classical
- 🎧 Dance
- 🎤 HipHop
- 🎷 Jazz

---

## 🛠️ Technologies Used

- 🐍 Python
- 🤖 Scikit-learn
- 📊 Pandas
- 🌳 Decision Tree Classifier
- 🔗 Graphviz
- 📓 Jupyter Notebook
- 💻 VS Code

---

## 📂 Project Structure

```text
Machine_Learning/
│
├── ML-Projects.ipynb
├── music.xlsx
├── music-recommender.joblib
├── music-recommender.dot
├── music-recommender.png
│
└── README.md
```
## 📄 File Description

| File                       | Purpose                       |
| -------------------------- | ----------------------------- |
| `ML-Projects.ipynb`        | Main Python/ML implementation |
| `music.xlsx`               | Dataset                       |
| `music-recommender.joblib` | Saved trained model           |
| `music-recommender.dot`    | Decision Tree structure       |
| `music-recommender.png`    | Visual Decision Tree          |
| `README.md`                | Project documentation         |

---
## 🚀 Step-by-Step Setup
### 1️⃣ Clone the Repository
```
 git clone <your-repository-url
```
Move into the project:

```
cd Machine_Learning
```
### 2️⃣ Create a Virtual Environment
Create a Python virtual environment:
```
python -m venv .venv
```
Activate it on Windows:
```
.venv\Scripts\activate
```
You should see something similar to:
```
(.venv) PS C:\Users\...\Machine_Learning>
```
### 3️⃣ Install Required Libraries
Install the required Python packages:
```
pip install pandas scikit-learn openpyxl joblib
```
If you are using Jupyter Notebook:
```
pip install notebook
```















