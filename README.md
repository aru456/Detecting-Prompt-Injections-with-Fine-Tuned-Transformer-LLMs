### **Detecting Prompt Injections with Fine-Tuned Transformer LLMs - Binary Text Classification**  

This repository contains the source code and model files for the project:  
**"Fine-Tuning Large Language Models for Enhancing Binary Text Classification"**.  

#### **Overview**  
The project focuses on fine-tuning pre-trained transformer-based models, such as **RoBERTa** and **XLNet**, for the specialized task of **prompt injection detection**. The goal is to classify text prompts as either *malicious* or *benign* with high accuracy and robustness.  

#### **Key Components**  
- **Dataset**: A labeled dataset of benign and malicious prompts sourced from the Hugging Face library ([Prompt Injection Dataset](https://huggingface.co/datasets/deepset/prompt-injections)).  
- **Model**: Fine-tuned **RoBERTa** model optimized for binary text classification tasks.  
- **Code Implementation**:  
    - Data preprocessing and analysis  
    - Model training with hyperparameter optimization  
    - Evaluation of performance metrics (Accuracy, Precision, Recall, F1-Score)  
- **Results**: Significant improvements in evaluation metrics, demonstrating the importance of task-specific fine-tuning.
