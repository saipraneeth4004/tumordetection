# tumordetection
# Brain Tumor Detection (CNN)

This project is a basic implementation of a Convolutional Neural Network (CNN) to classify brain MRI images as **tumor** or **no tumor**.

---

## What this project does

* Loads a brain tumor image dataset
* Preprocesses images using resizing and normalization
* Trains a CNN model using TensorFlow/Keras
* Predicts whether a given image contains a tumor

---

## Tech Used

* Python
* TensorFlow / Keras
* OpenCV
* NumPy
* Matplotlib

---

## Dataset

* Dataset contains two classes:

  * `tumor`
  * `no_tumor`

* Images are resized to **224 x 224**

---

## Model Details

* CNN Architecture:

  * Conv2D → ReLU → MaxPooling
  * Conv2D → ReLU → MaxPooling
  * Conv2D → ReLU

* Final output layer for binary classification

* Training:

  * Epochs: 5
  * Batch size: 32
  * Validation split: 20%

---

## How to Run

1. Install dependencies:

```bash
pip install tensorflow opencv-python matplotlib
```

2. Open the notebook:

```bash
jupyter notebook VRSU_Project.ipynb
```

3. Run all cells step by step

---

## Prediction

* Upload an image
* Model outputs:

  * **Tumor Detected**
  * **No Tumor**

---

## Limitations

* Trained for only 5 epochs (low accuracy possible)
* No model saving/loading
* Runs in notebook (not deployed)
* Basic CNN (not optimized)

---

## Future Improvements

* Increase training epochs
* Use better architecture (ResNet, VGG)
* Save and reuse trained model
* Deploy using Streamlit or web app

---

