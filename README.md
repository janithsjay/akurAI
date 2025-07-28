# AkurAI

AkurAI is a Sinhala character recognition system built initially using the K-Nearest Neighbors (KNN) algorithm. It focuses on classifying individual Sinhala characters from handwritten or printed input. The project aims to evolve into a complete AI-powered OCR solution by progressively incorporating more advanced machine learning and deep learning techniques.

## Key Features

- Simple and intuitive design to help students understand ML basics.
- Uses K-Nearest Neighbors (KNN) for classification.
- Can be expanded into a full-fledged OCR system with support for entire words and sentences.

---

## 🔍 How KNN Works

KNN is a simple, yet powerful machine learning algorithm used for classification and regression. It works based on **similarity**: it predicts the class of a data point by looking at the 'k' closest labeled data points in the feature space.

### Steps:
1. Choose the number of neighbors (k).
2. Measure the distance between the new point and all training points.
3. Select the k closest neighbors.
4. Do a majority vote (for classification) or average (for regression).

---

## 📏 Distance Measurement

KNN relies heavily on measuring distances between points. The most common method used is **Euclidean distance**.

### 🧮 Euclidean Distance Formula (2D)

For two points `P(x₁, y₁)` and `Q(x₂, y₂)`:

distance = √((x₂ - x₁)² + (y₂ - y₁)²)

For N-dimensional points:

distance = √(Σ (xi - yi)²)


---

## 👨‍🏫 Educational Use Case

This project is designed to be:
- Beginner-friendly for students learning ML.
- A visual and interactive way to understand how characters can be classified based on similarity.
- Modular for upgrades like using CNNs, Tesseract integration, or deep learning models in the future.

---

## 🛠️ Future Improvements

- Add convolutional neural networks (CNNs) for better image understanding.
- Train a full OCR model to detect whole words/sentences.
- Add GUI or web interface for real-time predictions.
- Export models and make them deployable on web/mobile.

