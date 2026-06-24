# 🍛 Indian Cuisine Classifier

A deep learning image classification project that identifies Indian food dishes from images using a **DenseNet-based CNN architecture**, trained on a curated dataset of Indian cuisine.

---

## 📌 Project Overview

This project builds and trains a convolutional neural network to classify images of Indian dishes into their respective categories. The pipeline covers everything from dataset preparation and model training to evaluation and inference via a simple app.

---

## 🗂️ Project Structure

├── filtered_dataset/              # Curated dataset used for training/testing

├── models/                        # Saved model artifacts

├── temp_downloads/                # Temporary storage for downloaded data

├── app.py                         # Run predictions on new images

├── download_data.py               # Fetch and prepare the dataset

├── model6_densenet.py             # DenseNet model training script

├── model6_densenet.h5             # Trained model weights

├── test_model.py                  # Evaluate the trained model

├── densenet_training_plots.html   # Training performance visualization

├── densenet_accuracy_plot.html    # Accuracy visualization

├── indian_food_classifier_plots.svg

├── accuracy_calculation_diagram.svg

├── model6_results.png             # Sample model output

└── 2nd_result.png                 # Additional sample result

---

## ⚙️ How It Works

| Step | Script | Description |
|------|--------|-------------|
| 1. Data Preparation | `download_data.py` | Collects and organizes the Indian food image dataset |
| 2. Model Training | `model6_densenet.py` | Trains a DenseNet CNN on the curated dataset |
| 3. Evaluation | `test_model.py` | Evaluates model accuracy with visual plots |
| 4. Inference | `app.py` | Loads trained model and classifies new images |

---

## 🚀 Getting Started

**1. Clone the repository:**
```bash
git clone https://github.com/bhargavajshetty/Indian-Cuisine-Classifier.git
cd Indian-Cuisine-Classifier
```

**2. Install dependencies:**
```bash
pip install tensorflow numpy pandas matplotlib
```

**3. Prepare the dataset:**
```bash
python download_data.py
```

**4. Train or evaluate the model:**
```bash
python model6_densenet.py   # train
python test_model.py        # evaluate
```

**5. Run the app:**
```bash
python app.py
```

---

## 📊 Results

Training performance and accuracy plots are available in:
- `densenet_training_plots.html`
- `densenet_accuracy_plot.html`
- `indian_food_classifier_plots.svg`

Sample classification outputs: `model6_results.png`, `2nd_result.png`

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat&logo=keras&logoColor=white)

- **Model Architecture:** DenseNet CNN
- **Libraries:** TensorFlow / Keras, NumPy, Pandas, Matplotlib
- **Visualization:** HTML plots, SVG diagrams

---

## 👤 Author

**Bhargava J Shetty**  
[GitHub](https://github.com/bhargavajshetty)
