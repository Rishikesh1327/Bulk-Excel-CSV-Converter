# Bulk Excel ↔ CSV Converter using Python (Google Colab)

---

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/9bc31bbc-de7e-40bd-aac4-a7f416012ded" />

---

This project is a simple Python automation script built using **Pandas** and **Google Colab** that allows you to bulk convert:

- Excel (.xlsx) → CSV (.csv)
- CSV (.csv) → Excel (.xlsx)

It works directly with **Google Drive** and is beginner-friendly.

---

## 🔹 Features
- Convert multiple Excel and CSV files in one go
- Automatically detects file type
- Downloads:
  - Single file directly
  - Multiple files as a ZIP
- No local setup required (runs on Google Colab)

---

## 🔹 Technologies Used
- Python
- Pandas
- Google Colab
- Google Drive API
- ZIP file handling

---

## 🔹 How It Works
1. Create a folder named **`Convert All Files`** in Google Drive
2. Upload any number of `.csv` or `.xlsx` files into it
3. Run the notebook in Google Colab
4. Files are converted automatically:
   - Excel → CSV
   - CSV → Excel
5. Converted files are downloaded:
   - Single file → Direct download
   - Multiple files → ZIP file download

---

## 🔹 Use Case
- Office automation
- Data analysis preprocessing
- Bulk file format conversion
- Saving manual effort and time

---


---

# 🔹 Requirements

```txt
pandas
openpyxl

