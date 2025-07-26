# **AI-Powered Document Processing System**  
![Python](https://img.shields.io/badge/Python-3.8+-blue.svg) ![License](https://img.shields.io/badge/License-MIT-green.svg)  
An **AI-powered document processing system** that uses **OCR and NLP** to extract and analyze text from documents. It supports **images (JPG, PNG)** and **PDFs**, and performs **Named Entity Recognition (NER)** using Hugging Face models. The system provides a simple **Gradio web interface** for easy interaction.  
## **Features**
- ✅ Extract text from PDFs and Images using **EasyOCR**  
- ✅ Perform **Named Entity Recognition (NER)** using **BERT model**  
- ✅ Simple **Gradio Web UI** for user interaction  
- ✅ Works on **Google Colab or Local Machine**  
- ✅ Supports **JPG, PNG, PDF** formats  
## **Project Structure**
ai-document-processor/
│
├── app.py              # Main application script
├── requirements.txt    # Project dependencies
├── README.md           # Project documentation
├── notebook.ipynb      # Colab-ready notebook
└── screenshots/        # UI and output screenshots
## **Tech Stack**
- **Python 3.8+**
- [EasyOCR](https://github.com/JaidedAI/EasyOCR)
- [Transformers (Hugging Face)](https://huggingface.co/)
- [Gradio](https://gradio.app/)
- [pdfplumber](https://github.com/jsvine/pdfplumber)
## **Run on Google Colab**
Click below to run this project in Google Colab:  
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](PUT_YOUR_COLAB_LINK_HERE)
## **Installation (Local Setup)**
Clone the repository:
```bash
git clone https://github.com/YOUR-USERNAME/ai-document-processor.git
cd ai-document-processor
Install dependencies:
```bash
pip install -r requirements.txt
Run the application:
```bash
python app.py
## **Usage**
1. Upload **PDF or Image** via Gradio UI  
2. Extracted text and detected entities will appear in the output  
3. Future update: Download results as JSON  
## **Output Example**
```json
{
  "Extracted Text": "Invoice number 12345 for $500",
  "Entities": [
    {"entity": "B-MISC", "word": "Invoice", "score": 0.99},
    {"entity": "B-MONEY", "word": "$500", "score": 0.98}
  ]
}
## **Screenshots**
*(Add screenshots in the `screenshots/` folder and reference them here)*
## **Future Enhancements**
✔ Add **Document Type Classification** (Invoice, ID, etc.)  
✔ Enable **Key-Value Extraction**  
✔ Export **results as downloadable JSON**  
✔ Deploy on **Streamlit or FastAPI**  
## **License**
This project is licensed under the **MIT License*
