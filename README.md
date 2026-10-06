# BLIP Image Captioning & Visual Question Answering

A Computer Vision / Multimodal AI project using Salesforce BLIP and Hugging Face Transformers.

This project demonstrates two multimodal AI capabilities:

- Image Captioning
- Visual Question Answering (VQA)

The model analyzes an image and either generates a natural-language description or answers questions about the visual content.

## Project Overview

The project uses pretrained BLIP (Bootstrapping Language-Image Pre-training) models from Salesforce through the Hugging Face Transformers library.

The same image is used for two different tasks:

1. Generate a caption describing the image.
2. Ask natural-language questions about the image and generate answers.

This demonstrates how a vision-language model can connect visual information with natural-language understanding.

## Technologies

- Python
- PyTorch
- Hugging Face Transformers
- Salesforce BLIP
- PIL (Python Imaging Library)
- Google Colab
- Computer Vision
- Multimodal AI
- Visual Question Answering (VQA)

## Models

The project uses the following pretrained models:

- `Salesforce/blip-image-captioning-base`
- `Salesforce/blip-vqa-base`

No model training or fine-tuning was performed. The project uses pretrained models for inference.

## Features

### Image Captioning

The image captioning model generates a natural-language description of the image.

Example:

BLIP Caption: a group of cats sitting in the grass

### Visual Question Answering

The VQA model answers natural-language questions about the contents of an image.

Example questions and answers:

Question: What animal is in the image?  
Answer: cat

Question: What is the cat doing?  
Answer: sitting

Question: Is there a cat in the image?  
Answer: yes

Question: Where is the cat?  
Answer: in front of house

## How It Works

The workflow consists of the following steps:

1. Upload an image.
2. Load the pretrained BLIP model.
3. Process the image using a BLIP processor.
4. Generate an image caption or process a visual question.
5. Generate the model output.
6. Decode the generated tokens into natural language.
7. Display the result.

## Project Structure

```text
BLIP_Image_Captioning_VQA/
│
├── BLIP_Image_Captioning_VQA.ipynb
├── README.md
├── requirements.txt
└── .gitignore

## Installation

Install the required Python packages:

```bash
pip install -r requirements.txt
```

## Key Concepts Demonstrated

This project demonstrates practical concepts in:

- Multimodal AI
- Computer Vision
- Vision-Language Models (VLMs)
- Image Captioning
- Visual Question Answering
- Transformer-based models
- Hugging Face Transformers
- Model inference
- Natural Language Generation

## Model Limitations

This project uses pretrained BLIP models without additional training or fine-tuning.

Therefore, the quality of the generated captions and answers depends on the capabilities and limitations of the pretrained models.

The model may sometimes:

- Misidentify objects
- Produce incomplete answers
- Give overly general descriptions
- Misinterpret spatial relationships
- Produce incorrect answers to complex questions

The project is intended as a demonstration of multimodal AI inference rather than a production-ready vision system.

## Future Improvements

Possible future improvements include:

- Fine-tuning BLIP on a domain-specific dataset
- Adding more images and automated evaluation
- Building a web interface using Flask or Streamlit
- Adding object detection
- Comparing different vision-language models
- Integrating the model into a larger multimodal AI application

## Author

İrem Kurşun

Computer Engineering | AI & Multimodal AI | E-Invoicing & Technology
