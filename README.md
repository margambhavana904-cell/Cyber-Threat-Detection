# Event Profile-Driven Artificial Neural Networks (ANN) for Identifying Cyber Threats

An advanced machine learning project designed to detect and identify potential cyber threats and network anomalies by building event profiles and processing them through an Artificial Neural Network (ANN).

---

## 🚀 Project Overview
Traditional security systems often rely on static signatures to detect cyber attacks, which can fail against zero-day exploits. This project introduces a dynamic approach by creating **Event Profiles** based on user and network activity patterns. These profiles are then classified using a deep learning-based Artificial Neural Network (ANN) to identify malicious behaviors with high accuracy.

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Frameworks/Deep Learning:** TensorFlow / Keras
* **Data Processing:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Development Environment:** Jupyter Notebook (VS Code)

## 📊 Dataset Structure
The system processes data files containing network traffic metrics and user behaviors. 
* **`event_profiling_data.csv`**: The dataset utilized for extracting system profiles, training the model, and validating threat classification metrics.

## 🧠 Model Architecture (ANN)
The core of this system is a multi-layer Artificial Neural Network structured as follows:
1. **Input Layer:** Accepts normalized features derived from the event profile data.
2. **Dense Hidden Layers:** Equipped with `ReLU` activation functions and `Dropout` regularization layers to improve performance and prevent overfitting.
3. **Output Layer:** Features a `Sigmoid` (or `Softmax`) activation function to output a probability score indicating whether an event profile constitutes a threat or benign activity.

---

## 💻 How to Run Locally

### 1. Clone the Repository
```bash
git clone [https://github.com/margambhavana904-cell/Cyber-Threat-Detection.git](https://github.com/margambhavana904-cell/Cyber-Threat-Detection.git)
cd Cyber-Threat-Detection
