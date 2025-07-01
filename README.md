# image-captioning-using-CNN-LSTM

Automatically generate human-like captions for images using deep learning.  
📁 **Dataset Used**: [Flickr8k Image Captioning Dataset](https://www.kaggle.com/datasets/adityajn105/flickr8k)

---

## 📌 Project Overview

This project demonstrates how deep learning can be used to interpret and describe images in natural language. It combines image processing and natural language processing (NLP) using a hybrid model of CNN and RNN (LSTM) to generate meaningful captions for input images.

---

## 💻 Technologies & Libraries Used

- **Python** (core language)
- **TensorFlow** or **PyTorch** – Deep learning frameworks  
- **Keras** – Simplified model building  
- **OpenCV / PIL** – Image handling and processing  
- **NLTK / SpaCy** – Text preprocessing and cleaning  
- **Matplotlib / Seaborn** – (optional) for visualization  

---

## 🔄 Workflow

1. **Load Dataset**: Load image files and associated captions from Flickr8k
2. **Preprocess Text**: Clean captions, tokenize, pad sequences, build vocabulary
3. **Extract Image Features**: Use a pre-trained CNN (like ResNet50 or VGG16)
4. **Create Training Data**: Combine image features with partial captions → next word
5. **Train Model**: CNN for image + LSTM for language sequence generation
6. **Generate Captions**: Predict captions word by word for a new image

---

## 🚀 How to Run the Project

1. Clone the repository  
2. Install dependencies  
   ```bash
   pip install -r requirements.txt
   ```
3. Download the dataset from [Flickr8k on Kaggle](https://www.kaggle.com/datasets/adityajn105/flickr8k)  
4. Run the main training script:  
   ```bash
   python main.py
   ```

