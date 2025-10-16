Here’s your final professional README.md for your repo pk_fake_dataset_json — in exact same structure, but correctly adapted for your JSON dataset instead of CSV.

# pk_fake_dataset_json
A synthetic dataset of 150+ fake Pakistani individuals for AI & data analysis projects.

# 🇵🇰 Pakistani People Dataset (Synthetic)
![License: CC0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)
![Made with 💚 in Pakistan](https://img.shields.io/badge/Made%20with-%F0%9F%92%9A%20in%20Pakistan-green)
![Format: JSON](https://img.shields.io/badge/Format-JSON-blue)
![Records: 150+](https://img.shields.io/badge/Records-150+-orange)

A **synthetic dataset** of **150+ Pakistani individuals**, created for use in **AI, data science, and machine learning** projects.  
This dataset reflects realistic Pakistani demographic patterns — while containing **no personal or real data** — making it completely safe and open for **educational, academic, and research purposes**.

---

## 📊 Dataset Overview

| Attribute | Description |
|------------|-------------|
| **id** | Unique numeric identifier |
| **full_name** | Randomly generated Pakistani name |
| **gender** | Male / Female |
| **age** | Age between 18 and 65 years |
| **city** | Major Pakistani cities (Lahore, Karachi, Islamabad, etc.) |
| **province** | Province corresponding to the city |
| **occupation** | Common professions in Pakistan |
| **education** | Matric, Intermediate, Bachelor, Master, PhD |
| **phone_number** | Synthetic Pakistani-format number (+92...) |
| **email** | Fake but valid email format |
| **income** | Estimated monthly income in PKR |
| **marital_status** | Single / Married |
| **language** | Regional language (Urdu, Punjabi, Pashto, etc.) |

---

## 🧠 Purpose

This dataset is ideal for:

- 🤖 Machine Learning model testing  
- 📈 Data visualization and analytics  
- 🧮 Statistics, probability, and data cleaning exercises  
- 🧠 AI/NLP experimentation using JSON data  
- 🎓 Educational and research projects  

---

## 🧾 Example JSON Structure

```json
[
  {
    "id": 1,
    "full_name": "Example Person",
    "gender": "Male",
    "age": 31,
    "city": "Karachi",
    "province": "Sindh",
    "occupation": "Teacher",
    "education": "Bachelor",
    "phone_number": 923001234567,
    "email": "example@gmail.com",
    "income": 75000,
    "marital_status": "Married",
    "language": "Urdu"
  }
]

🧩 File Information

File Name: pakistani_people_dataset.json
Records: 150+
File Type: JSON (Array of Objects)
Encoding: UTF-8

⚙️ How to Use
🔹 In Python (pandas)
'''python
[import pandas as pd

url = "https://raw.githubusercontent.com/CM-Kali/pk_fake_dataset_json/main/pakistani_people_dataset.json"
df = pd.read_json(url)

print(df.head())
print(df.info())
]
🔹 In JavaScript (Fetch API)
'''fetch('pakistani_people_dataset.json')
  .then(response => response.json())
  .then(data => console.log(data.slice(0, 5)));

💡 Applications

Data preprocessing & cleaning practice

JSON structure parsing & transformation

Data visualization dashboards

Mock APIs and backend testing

AI & ML model prototyping

⚠️ License & Disclaimer

This dataset is 100% synthetic and was created for educational and testing purposes only.
It contains no real or personal information and can be freely used in non-commercial projects under the CC0 License.

✨ Author

CMADEEL
Flutter Developer & Data Enthusiast
GitHub: CM-Kali

⭐ If you find this dataset useful, please give this repository a star!
