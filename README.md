# Image Captioning System

An AI-based system that generates textual descriptions for images using computer vision and natural language processing techniques. This project combines a pre-trained **VGG16** model for feature extraction and an **LSTM-based** neural network for sequence generation.

## Features
- **Image Feature Extraction**: Extracts feature vectors using a pre-trained **VGG16** model.
- **Text Preprocessing**: Cleans and tokenizes captions, creating a vocabulary for training.
- **Caption Generation**: Combines image features and LSTM for meaningful caption generation.
- **Evaluation**: Uses **BLEU** scores (BLEU-1 to BLEU-4) for model performance evaluation.
- **Real-Time Captioning**: Generate captions for new images using the trained model.

## Technologies Used
- **Python**, **TensorFlow** / **Keras**
- **VGG16** for image feature extraction
- **LSTM** for sequence modeling
- **BLEU Score** for evaluation

## Dataset
- **Flickr8k Dataset** (8,000 images with captions).

## How It Works
1. **Feature Extraction**: Extracts image features using **VGG16**.
2. **Text Preprocessing**: Cleans and tokenizes captions, adding **startseq** and **endseq** for training.
3. **Model Training**: Trains a combined **CNN-LSTM** model for caption generation.
4. **Caption Generation**: Generates captions one word at a time.
5. **Evaluation**: Evaluates model accuracy using **BLEU scores**.

## Setup and Usage

### Clone the repository  :
```bash
git clone https://github.com/your-username/image-captioning-system.git


