# AI-Powered Invoice Text Extraction

## 📌 Overview
AI-Powered Invoice Text Extraction is an advanced machine learning-based invoice processing tool powered by Azure Form Recognizer and Optical Character Recognition (OCR). It automates data extraction from invoices, improving accuracy and efficiency for financial document management.

## 🎯 Objective
The aim of this project is to develop a system capable of automatically extracting key information from invoices to streamline the data entry process.

### Key Objectives:
- **Automated Data Extraction**: Accurately extract essential information such as vendor details, invoice dates, total amounts, and item descriptions.
- **Label Prediction**: Train machine learning models to predict predefined labels/features from extracted text, including vendor names, invoice IDs, due dates, and more.
- **Accuracy and Efficiency**: Ensure high accuracy and efficiency in the extraction process to minimize errors and reduce manual effort.
- **Scalability**: Build a scalable solution capable of handling large volumes of invoices across various formats and layouts.
- **Integration**: Seamlessly integrate the system with existing workflows and accounting tools.

## 🚀 Features
- Extracts structured invoice data (Vendor, Customer, Invoice ID, Amount, Dates, etc.).
- Utilizes Azure AI for high-accuracy OCR and form recognition.
- Implements **KNN-based OCR** and **Bidirectional LSTMs** for text recognition and contextual understanding.
- Processes invoices efficiently and exports structured data.
- Saves extracted data in a secure Azure Blob Storage location.

## 🏗️ Architecture
### OCR System (KNN Algorithm)
- Uses the **K-Nearest Neighbors (KNN)** algorithm trained on the MNIST dataset.
- Extracts text from invoice images with confidence scores and line numbers.

### Deep Learning with Bidirectional LSTM
- Captures contextual information from both past and future tokens.
- Enhances sequence labeling and text classification.
- Uses a softmax output layer for probability-based label confidence.

## 🛠️ Technologies Used
- **Azure AI Form Recognizer** for document analysis.
- **Python** for processing and automation.
- **Pandas** for data manipulation.
- **PySpark** and **Databricks** for large-scale data handling.
- **Bidirectional LSTMs** for deep learning-based text extraction.
- **Azure Blob Storage** for cloud storage.

## 📂 Project Structure
```
|-- Invoice-Test-Extraction.ipynb  # Machine Learning workflow
|-- ML.ipynb                       # Additional ML components
|-- OCR.ipynb                      # OCR processing
|-- utilities.ipynb                # Utility functions and data handling
```

## 📖 Getting Started
### Prerequisites
- Azure subscription with Form Recognizer enabled.
- Python 3.8+
- Install dependencies:  
  ```bash
  pip install azure-ai-formrecognizer pandas openpyxl pyspark
  ```

### Running the Project
1. Clone the repository:  
   ```bash
   git clone https://github.com/HareenaChowdary/AI-Powered-Invoice-Text-Extraction.git
   cd AI-Powered-Invoice-Text-Extraction
   ```
2. Run the Jupyter notebooks to extract and analyze invoices.

## 🌟 Why Databricks?
- **Scalability**: Handles large volumes of invoices efficiently.
- **Managed Environment**: Abstracts infrastructure complexities.
- **Spark Integration**: Enables distributed computing for large-scale processing.

## 🤝 Contributing
Feel free to submit pull requests and contribute to this project!

## 📧 Contact
Looking for collaboration or have questions? Reach out on [LinkedIn Profile](https://www.linkedin.com/in/hareena-chowdary-polavaram/) .

---
🚀 **Invoice Text Extraction – Transforming invoices into structured insights with AI!**

