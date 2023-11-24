# Typo Detector with OpenVINO™
 
Typo detection in AI is the process of identifying and correcting typographical errors in text data using machine learning algorithms. The goal is to enhance accuracy, readability, and usability of text by pinpointing and rectifying mistakes in writing. AI-based typo detectors leverage techniques like natural language processing (NLP), machine learning (ML), and deep learning (DL).
 
## Overview
 
This project demonstrates a typo detection system utilizing the OpenVINO™ (Open Visual Inference & Neural Network Optimization) toolkit. It identifies typographical errors, including misspellings and homophone errors, within sentences.
 
### Installation
 
Use the provided command for the installation of required packages via pip.
 
### Table of Contents:
 
- **Imports:** Necessary libraries and modules required for the code execution.
- **Methods:** Two distinct methods for running the inference of the typo detector with OpenVINO runtime.
  - **Method 1 - Using Hugging Face Optimum:** Utilizes the Hugging Face Optimum API for model conversion to OpenVINO IR format.
  - **Method 2 - Converting the model to OpenVINO IR:** Manually converts the PyTorch model to OpenVINO IR format for inference.
- **Select Inference Device:** Interface to select the device for running inference using OpenVINO.
- **Hugging Face Optimum Intel Library:** Details and steps to use the Hugging Face Optimum Intel library for typo detection.
- **Converting the Model to OpenVINO IR:** Step-by-step process to convert the model to OpenVINO IR format.
- **Inference:** Functions and methods for inference and typo detection.
- **Helper Functions:** Supplementary functions to assist in tokenization, inference, and typo detection.
- **Demo:** Demonstration of the typo detection system using sample sentences and showing detected typos.
 
### Usage
 
1. **Installation:** Set up the environment with required libraries.
2. **Method Selection:** Choose between the provided methods for typo detection.
3. **Device Selection:** Select the device for OpenVINO inference.
4. **Running Inference:** Execute the code blocks to experience the typo detection system.
5. **Customization:** Modify sentences or experiment with different text inputs for typo detection.
6. **Understanding Outputs:** Analyze the outputs to identify detected typos in the text.
 
## Workflow
 
This code repository demonstrates two distinct methods for typo detection using OpenVINO™, providing insights into model conversion, loading, and inference. Users can explore and compare the methods to understand their usage and efficiency.
 
### Method 1 - Hugging Face Optimum
 
This method leverages the Hugging Face Optimum Intel library for model loading, conversion, and inference. It facilitates the seamless conversion of Hugging Face Transformer models to OpenVINO IR format and allows the use of optimization on targeted hardware.
 
### Method 2 - Converting the Model to OpenVINO IR
 
This manual method showcases the process of converting a PyTorch-based model to OpenVINO IR format for optimized inference. It involves model conversion, compilation, and running inference with OpenVINO Runtime.
 
## Examples
 
The code includes demo sentences demonstrating typo detection using both methods. These examples showcase the system's capability to identify and highlight detected typos in the input text.
