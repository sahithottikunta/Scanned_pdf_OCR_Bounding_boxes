# 📄 Scanned PDF OCR with Bounding Boxes

This repository contains a Jupyter Notebook (`Analyze_a_scanned_PDF.ipynb`) that demonstrates how to **analyze scanned PDF files** by performing **OCR (Optical Character Recognition)** and extracting structured information with text cleaning and preprocessing.

## 🚀 Features
- Extract text from scanned PDFs using [Tesseract OCR](https://github.com/tesseract-ocr/tesseract).
- Use **PyMuPDF (`fitz`)** to load and work with PDF pages.
- Apply regex-based cleaning to remove OCR artifacts.
- Preview bounding boxes and text extraction results.
- Save structured output for further analysis.

## 📂 Project Structure
.
├── Analyze_a_scanned_PDF.ipynb # Main notebook with OCR + text cleaning
└── README.md # Project documentation

## 🛠️ Requirements
- Python 3.8+
- Jupyter Notebook / JupyterLab
- Install required Python libraries:
  ```bash
  pip install pymupdf pytesseract matplotlib
Install Tesseract OCR:
sudo apt install tesseract-ocr
Usage
1) Clone this repository:
   git clone https://github.com/sahithottikunta/Scanned_pdf_OCR_Bounding_boxes.git
cd Scanned_pdf_OCR_Bounding_boxes
2)Open the notebook:
  jupyter notebook Analyze_a_scanned_PDF.ipynb
3)Update the pdf_path variable with your scanned file:
  pdf_path = "your_scanned_file.pdf"
📊 Example Output

Raw OCR text → noisy text directly from the scan.

Cleaned text → processed with regex to remove artifacts.

Bounding boxes → word/line positions for structured document analysis.

🤝 Contributing

This is a personal/academic project. Contributions are welcome via issues or pull requests.

⚖️ License

All Rights Reserved.
This project is for personal, academic, or internal use. You may not copy, modify, distribute, or use it commercially without explicit permission.This was done for the practice
