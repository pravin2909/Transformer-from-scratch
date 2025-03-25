# Transformer-Based Machine Translation  
This repository implements a transformer-based machine translation model using PyTorch. The model is designed to translate between English and Italian using a custom dataset.  

## Features  
- Implements a transformer model with an encoder-decoder architecture and multi-head attention.  
- Supports bilingual dataset processing with tokenization and padding.  
- Configurable training pipeline with adjustable hyperparameters in `config.py`.  
- Uses PyTorch for efficient training and optimized tensor operations.  

## Project Structure  
- **datasets.py** – Handles dataset preprocessing and tokenization.  
- **model.py** – Defines the transformer model architecture.  
- **train.py** – Contains the training script.  
- **config.py** – Stores configuration settings such as hyperparameters and file paths.  

## Requirements  
Python 3.8 or later

PyTorch

NumPy

Torchvision

Tokenizers
## License 
This project is licensed under the MIT License.
