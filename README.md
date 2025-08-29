
# 🔴 Real-time Violence Detection System

## 📌 Problem Statement

CCTV surveillance is widely deployed in public and private spaces, but most systems lack **automatic violence detection features**.
Manual monitoring is:

* Inefficient and time-consuming.
* Prone to human error.
* Causes delays in real-time response.

This project proposes a **real-time violence alert system** using deep learning to automate violence detection and improve **public safety**.

---

## 🚀 Methodology

### 📂 Dataset

* **Source:** [Real Life Violence Situations Dataset (Kaggle)](https://www.kaggle.com/datasets/mohamedmustafa/real-life-violence-situations-dataset)
* **Size:** 1000+ videos each in **Violence** and **Non-Violence** categories.
* **Preprocessing:** Frame extraction, resizing, normalization, and augmentation.

### 🧠 Model Training

* **Architecture:** MobileNetV2
* **Input:** Real-time video frames.
* **Output:** Classified as **Violence** or **Non-Violence**.

---

## 🧠 MobileNetV2 – Why This Model?

* A **53-layer deep CNN** optimized for real-time video classification.
* **Lightweight & fast**, suitable for live CCTV footage.
* Uses **inverted residual structure** for efficiency.
* Employs **depthwise separable convolutions** to reduce computation without losing accuracy.

---

## 🖥️ Operating Environment

* **Programming Language:** Python
* **Frameworks:** TensorFlow / Keras, OpenCV
* **Development Environment:** Google Colaboratory
* **Hardware Acceleration:** Google GPU / TPU for model training

---

## 📊 Results

* **Best Epochs:** 31
* **Training Accuracy:** 96.17%
* **Training Loss:** 0.1121
* **Test Accuracy:** 95.77%
* **Test Loss:** 0.1163

---

## 🔍 Performance Metrics

| Class        | Precision | Recall | F1-Score |
| ------------ | --------- | ------ | -------- |
| Non-Violence | 0.95      | 0.96   | 0.96     |
| Violence     | 0.96      | 0.95   | 0.96     |
| **Accuracy** |           |        | **96%**  |
| Macro Avg    | 0.96      | 0.96   | 0.96     |
| Weighted Avg | 0.96      | 0.96   | 0.96     |

✅ **Predictions Summary:**

* **Correct Predictions:** 4606
* **Wrong Predictions:** 203

---

## 📌 Future Enhancements

* Improve accuracy with **larger and more diverse datasets**.
* Deploy on **edge devices** (Raspberry Pi, Jetson Nano) for real-world CCTV integration.
* Implement **real-time alerts & notifications** via SMS / IoT systems.
* Integrate with **cloud-based surveillance platforms**.

---

## 📜 License

This project is **open-source** and available under the **MIT License**.

---

## 👥 Contributors

* Contributions are welcome! 🎉
* Feel free to **fork** the repo, open **issues**, and submit **pull requests** 🚀

---

## 📂 Repository Details

* **Languages Used:**

  * Jupyter Notebook (100%)
* **Resources:**

  * Dataset: Kaggle Violence Dataset
  * Dependencies: TensorFlow, Keras, OpenCV

Do you want me to also **add installation & usage instructions** (like how to clone, install dependencies, and run detection on a video) so that someone can directly test your system?
