# 🏎️ Formula 1 Driver Penalties Analysis

**🔗 Project link:** [hazel-gandhi.github.io/formula1-scraper](https://hazel-gandhi.github.io/formula1-scraper/)

This project uses decision documents shared by the FIA after every race to determine:
- How many drivers are paying monetary fines
- How much they are fined
- How FIA's fine collection in 2024 compares to previous years

---

## 📁 Repo Guide

All detailed folders and analysis files are in this Google Drive:  
[Google Drive – Formula 1 Scraper Files](https://drive.google.com/drive/u/0/folders/1PMPUe7h7ya4IRPY8MhqS6okQuu6T8ySd)

### 📓 `fia-scraper-2024.ipynb`
The main scraper notebook that:
- Extracts all decision documents from the FIA website for 2024
- Downloads them as PDFs
- Scrapes them using Natural PDF  
(*Other years' scrapers are in the `notebooks` folder on Drive*)

### 📄 `pdfs` folder (Google Drive)
Contains:
- Year-wise folders
- All PDFs scraped from the FIA website used for analysis

### 📓 `notebooks` folder (Google Drive)
Includes:
- Individual scrapers for every year
- `analysis.ipynb` notebook used to generate charts

### 📊 `data` folder (Google Drive)
Contains:
- All CSVs created from the analysis
- Two key files per year:  
  (i) Monetary fines  
  (ii) Other categorized fines based on methodology

### 🖼️ Charts and Visuals
- Illustrator `.svg` files are available for all charts
- `ai2html-output` folder contains responsive scrollytelling charts

---

## 🎯 Project Goal

- Undertake a project involving complex scraping (Playwright + multi-PDF parsing)
- Create a visual narrative using **scrollytelling**

---

## ⚠️ Challenges

- Efficiently scraping hundreds of documents
- Categorizing fines accurately
- Manually verifying and improving the scraper after reviewing ~800–1000 PDFs per year

---

## 🔧 Things to Improve

- Add data from missing years (2016–2018) for better historical analysis
- Organize the repo better — avoid relying on Google Drive
- Improve the **design** and **layout** of the scrollytelling visual
