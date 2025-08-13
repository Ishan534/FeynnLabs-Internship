# Receipt OCR & Data Extraction System

## 📌 Overview
This project implements an **OCR-based receipt scanning pipeline** that extracts structured data from retail receipts and generates analytical reports.  
It processes scanned or camera-captured images of receipts and extracts key details such as:
- Store Name
- Purchase Date
- Total Amount
- Store Address
- Itemized List of Purchases
- Raw Text for reference

The extracted data is stored in a **Pandas DataFrame**, used for generating:
- 📊 Visualizations (spending over time, spending by store, etc.)
- 📄 Automated PDF Reports

This solution can be applied to:
- Expense tracking
- Financial auditing
- Retail analytics
- Personal finance management

---

## 🚀 Features
- **OCR Processing** using [PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR) (English model).
- **Image Preprocessing**: automatic rotation correction, skew adjustment, noise removal.
- **Field Extraction** using Regular Expressions.
- **Structured Storage** in Pandas DataFrame.
- **Visual Reports**: spending trends, store-based spending breakdown.
- **PDF Export** with summary tables & charts.

---

⚠ Limitations
CPU-only processing is slower (~2 minutes per receipt).

Highly blurred or damaged receipts may produce inaccurate results.

Only supports English-language receipts in the current version.

🔮 Future Improvements
GPU acceleration for faster processing.

Multi-language OCR support.

AI-based key-value field extraction for better layout adaptability.

Web dashboard for real-time analytics.

📄 License
This project is licensed under the MIT License.

🤝 Contributing
Pull requests are welcome!
If you have suggestions for improving parsing accuracy or visualization, feel free to contribute.
