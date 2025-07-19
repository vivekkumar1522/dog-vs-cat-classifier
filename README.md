# 🐶🐱 Dog vs Cat Classifier 🧠

A Convolutional Neural Network (CNN)-based image classification project built using TensorFlow and Keras that distinguishes between dog and cat images.

## 📁 Project Structure

- `Dog_vs_Cat_classifier.ipynb` — Jupyter notebook containing data preprocessing, model training, evaluation, and predictions.
- `/dataset/` — Folder containing the training and testing images (assumed structure).
- `/models/` — Saved models (optional).
- `README.md` — Project overview and instructions.

## 🧰 Tech Stack

- Python
- TensorFlow & Keras
- NumPy & Pandas
- Matplotlib & Seaborn
- Scikit-learn (for metrics)
- Jupyter Notebook

## 📊 Model Architecture

- Convolutional layers (Conv2D + MaxPooling2D)
- Dropout for regularization
- Flatten → Dense layers
- Output layer with Sigmoid activation (binary classification)

## 📈 Model Performance

- Training and validation accuracy and loss are plotted.
- Confusion matrix and classification report included for evaluation.
- Achieved high test accuracy (~94% depending on dataset and epochs).

## 📦 Dataset

You can download the dataset from Kaggle:

* [Dogs vs. Cats | Kaggle](https://www.kaggle.com/c/dogs-vs-cats)


## 📊 Evaluation Metrics

* Accuracy Score
* Confusion Matrix
* Classification Report (Precision, Recall, F1-Score)

## 🧠 Possible Improvements

* Data Augmentation (to reduce overfitting)
* Transfer Learning (e.g., using VGG16, ResNet)
* Hyperparameter tuning
* Better training/test split or K-fold CV

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss.

