# pk_fake_dataset_json

This repository contains a **synthetic dataset** representing fictional individuals from Pakistan.  
It is ideal for **data science projects**, **machine learning demos**, **testing**, and **educational use** where realistic, well-structured JSON data is required.

---

## 📁 Dataset Overview

- **File name:** `pakistani_people_dataset.json`  
- **Format:** JSON (Array of objects)  
- **Records:** 150+  
- **Encoding:** UTF-8  
- **Type:** Synthetic (Fictional data)  
- **Created by:** [CMADEEL](https://github.com/CM-Kali)

---

## 📄 Description

Each record represents a fictional person with demographic and occupational details commonly found across regions of Pakistan.  
This dataset has been generated for testing, learning, and demonstrating various data operations such as parsing, analysis, and visualization.

---

## 🧩 Data Fields

| Field | Description |
|--------|-------------|
| **id** | Unique identifier for each record |
| **full_name** | Full name of the individual |
| **gender** | Gender (Male / Female) |
| **age** | Age in years |
| **city** | City of residence |
| **province** | Province or territory in Pakistan |
| **occupation** | Current profession or role |
| **education** | Highest level of education |
| **phone_number** | Randomized local contact number |
| **email** | Generated email address |
| **income** | Monthly income in PKR |
| **marital_status** | Marital status |
| **language** | Primary spoken language |

---

## 📊 Example Structure

```json
[
  {
    "id": 1,
    "full_name": "Example Person",
    "gender": "Female",
    "age": 29,
    "city": "Lahore",
    "province": "Punjab",
    "occupation": "Engineer",
    "education": "Bachelor",
    "phone_number": 923000000000,
    "email": "example.person@gmail.com",
    "income": 85000,
    "marital_status": "Single",
    "language": "Urdu"
  }
]
💻 How to Use
▶️ Load in Python

import pandas as pd

url = "https://raw.githubusercontent.com/CM-Kali/pk_fake_dataset_json/main/pakistani_people_dataset.json"
df = pd.read_json(url)
print(df.head())


▶️ Load in JavaScript
fetch('pakistani_people_dataset.json')
  .then(response => response.json())
  .then(data => console.log(data.slice(0, 3)));

🧠 Applications

Data preprocessing and cleaning practice

Data visualization and analytics exercises

Model testing for AI/ML workflows

Educational and classroom demonstrations

Backend API testing and mock responses

⚠️ License & Disclaimer

This dataset is entirely synthetic and created for educational and demonstration purposes only.
It does not represent real people or actual personal information.

✨ Author

CMADEEL
Flutter Developer & Data Enthusiast
GitHub: CM-Kali

⭐ If you find this dataset useful, please give this repository a star!
