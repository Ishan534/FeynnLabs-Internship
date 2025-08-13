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

## 📂 Project Structure
