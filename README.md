# SmartSight: CaptionNet

SmartSight is an advanced image captioning system built using Convolutional Neural Networks (CNN) and Long Short-Term Memory (LSTM) networks. It processes an input image and generates context-aware, natural language descriptions using deep learning. Ideal for accessibility tools, media tagging, and AI-driven image understanding.

## 🔧 Technologies Used

* Python
* TensorFlow / Keras
* CNN (e.g., InceptionV3 or VGG16)
* LSTM
* NLTK / SpaCy for text preprocessing
* NumPy, Matplotlib, PIL

## 🚀 Features

* Extracts high-level features from images using pretrained CNN models
* Converts image features to descriptive text using LSTM
* Supports preprocessing, training, and prediction pipelines
* Easy to extend for other languages or custom vocabularies

## 📁 Project Structure

```
Image-Captioning-Using-CNN-and-LSTM/
├── model/              # Saved models
├── data/               # Dataset files
├── utils/              # Preprocessing and helper scripts
├── train.py            # Model training script
├── predict.py          # Inference script
├── app.ipynb           # Demo notebook
├── requirements.txt    # Required Python packages
```

## 📦 Installation

1. Clone the repo:

   ```bash
   git clone https://github.com/your-username/SmartSight-CaptionNet.git
   cd SmartSight-CaptionNet
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## 🧠 Training

```bash
python train.py
```

Make sure to preprocess the dataset using scripts in `utils/` before training.

## 📷 Predicting Captions

```bash
python predict.py --image path/to/image.jpg
```

## 📄 License

This project is licensed under the MIT License.

## 🔗 Project Link

[GitHub Repository](https://github.com/your-username/SmartSight-CaptionNet)
