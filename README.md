# Inscale Data Engineer Task Based Test Submission for Arif Zamri

This repository contains a comprehensive solution for a data engineering task involving advanced company profiling and data validation. The task involves working with UK company data to perform various data engineering steps including cleansing, deduplication, validation via external API (Companies House), enrichment, visualization, and summarization.

---

## 🧾 Objective

Develop a pipeline that processes and validates UK company data with the following stages:

1. **Data Collection** – Load and inspect a raw dataset (`Company.csv`).
2. **Profiling** – Understand structure, null values, data types, and distributions.
3. **Cleansing** – Identify and remove incomplete or problematic records with missing crucial fields like company name or primary address.
4. **Deduplication** – Detect and remove duplicate entries using company name and address as keys.
5. **Matching** – Validate against [Companies House API](https://developer.company-information.service.gov.uk/overview/) and retrieve official records.
6. **Enrichment** – Add validated names and registration numbers to the data.
7. **Reporting & Visualization** – Generate insights through charts: cleansing impact, duplicates, API matching success, enrichment coverage.
8. **Presentation & Delivery** – Generate summary statistics and export cleaned and enriched data.

---

## 🧰 Tech Stack

- **Python 3.11+**
- **Jupyter Notebook**
- **Pandas**
- **Plotly**
- **Requests**
- **Companies House REST API**

---

## 📦 Folder Structure

```
uk-company-profiling-api-matching/
├── data/
│   └── Company.csv
├── notebooks/
│   └── CluedIn_Company_Data_Profiling_and_Validation.ipynb
├── output/
│   └── company_enriched.csv
├── README.md
└── LICENSE
```

---

## 🔑 API Access

This solution integrates with the Companies House API. You must register a personal API key from [Companies House Developer Hub](https://developer.company-information.service.gov.uk/).

---

## 📊 Output Summary

The notebook generates:
- A cleaned, deduplicated, and enriched dataset.
- Pie charts for each phase: Cleansing, Deduplication, Matching, Enrichment.
- A dynamic summary for presentation use.

---

## ✅ How to Run

1. Clone this repo and install dependencies:
```bash
pip install pandas plotly requests
```

2. Place your `Company.csv` inside the `data/` folder.

3. Launch Jupyter and run the notebook:
```bash
jupyter notebook notebooks/CluedIn_Company_Data_Profiling_and_Validation.ipynb
```

4. Replace `API_KEY` variable in Section 5 with your key.

---

## ✍️ Author

**Arif Zamri**  
Crafting Scalable Data Culture
GitHub: [mmarifmz]
Coffee Session: +60.11 400 300 76

---

## 📜 License

This project is licensed under the MIT License.