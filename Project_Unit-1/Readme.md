# 📄 Smart Resume Parser 🤖

A simple NLP-based application that automatically extracts structured information from unstructured resume text using Hugging Face transformer models.

---

## 📌 Project Overview

Resumes come in many formats, making manual information extraction inefficient and error-prone ⚠️  
This project demonstrates how **Natural Language Processing (NLP)** 🧠 can be used to automatically extract key details from resumes.

### 🗂️ Extracted Fields
- 👤 Name  
- 🎓 University  
- 🏢 Company / Companies  

The system converts raw resume text into a structured format suitable for automated screening and analysis 📊.

---

## 🎯 Objective

- Understand the application of **Named Entity Recognition (NER)** in real-world text analysis  
- Extract meaningful information from unstructured resume data 📄  
- Compare how transformer-based models perform on extraction tasks  

---

## 🧠 Approach & Methodology

- 🤖 **NER Model Used:** dslim/bert-base-NER  
- 📚 **Library:** Hugging Face transformers  
- 🔧 **Pipeline:** pipeline("ner")

### 🔍 Extraction Logic
- 👤 **Name:** Identified using PER (Person) entities  
- 🏢 **Company:** Identified using ORG (Organization) entities  
- 🎓 **University:** Extracted using **regular expressions**, as educational institutions are not always reliably detected by NER models  

### 🧹 Post-processing
- Handles token fragmentation  
- Removes role/designation noise from company names  
- Filters duplicate company entries  
- Produces clean, structured output ✨  

---

## 🛠️ Tech Stack

- 🐍 Python 3  
- 🤗 Hugging Face Transformers  
- 🧠 Pre-trained BERT-based NER model  
- 🧩 Regular Expressions (Regex)  

---

## 📂 Project Structure

- 📓 PES2UG23CS379_p1.ipynb – Main notebook with implementation  
- 📑 PES2UG23CS379_p1.pdf – Assignment documentation  
- 📝 README.md – Project documentation  

---

## ▶️ How to Run

1. 📦 Install required libraries  
   pip install transformers torch  

2. Open the Jupyter Notebook:  
   jupyter notebook PES2UG23CS379_p1.ipynb  

3. Run all cells and provide resume text as input.

---

## Sample Output

=== Smart Resume Parser ===  
Name: Neha Patil  
University: PES University  
Companies: ['J.P. Morgan Chase & Co', 'General Electric']

---

## Observations

- NER performs well for Person and Organization extraction  
- University names require regex support for better accuracy  
- Post-processing significantly improves output quality  

---

## Author

Name: Neha Rajkumar Patil  
SRN: PES2UG23CS379  
Section: F  

---

## Academic Context

This project was completed as part of Unit 1 – GenAI & NLP coursework and focuses on applying transformer-based models for analysis and extraction tasks.

---

## License

This project is intended for academic and educational use only.
You said:
use emojies
ChatGPT said:
# 📄 Smart Resume Parser 🤖

A simple NLP-based application that automatically extracts structured information from unstructured resume text using Hugging Face transformer models.

---

## 📌 Project Overview

Resumes come in many formats, making manual information extraction inefficient and error-prone ⚠️  
This project demonstrates how **Natural Language Processing (NLP)** 🧠 can be used to automatically extract key details from resumes.

### 🗂️ Extracted Fields
- 👤 Name  
- 🎓 University  
- 🏢 Company / Companies  

The system converts raw resume text into a structured format suitable for automated screening and analysis 📊.

---

## 🎯 Objective

- Understand the application of **Named Entity Recognition (NER)** in real-world text analysis  
- Extract meaningful information from unstructured resume data 📄  
- Compare how transformer-based models perform on extraction tasks  

---

## 🧠 Approach & Methodology

- 🤖 **NER Model Used:** dslim/bert-base-NER  
- 📚 **Library:** Hugging Face transformers  
- 🔧 **Pipeline:** pipeline("ner")

### 🔍 Extraction Logic
- 👤 **Name:** Identified using PER (Person) entities  
- 🏢 **Company:** Identified using ORG (Organization) entities  
- 🎓 **University:** Extracted using **regular expressions**, as educational institutions are not always reliably detected by NER models  

### 🧹 Post-processing
- Handles token fragmentation  
- Removes role/designation noise from company names  
- Filters duplicate company entries  
- Produces clean, structured output ✨  

---

## 🛠️ Tech Stack

- 🐍 Python 3  
- 🤗 Hugging Face Transformers  
- 🧠 Pre-trained BERT-based NER model  
- 🧩 Regular Expressions (Regex)  

---

## 📂 Project Structure

- 📓 PES2UG23CS379_p1.ipynb – Main notebook with implementation  
- 📑 PES2UG23CS379_p1.pdf – Assignment documentation  
- 📝 README.md – Project documentation  

---

## ▶️ How to Run

1. 📦 Install required libraries  
pip install transformers torch


2. 📓 Open the Jupyter Notebook  
jupyter notebook PES2UG23CS379_p1.ipynb


3. ▶️ Run all cells and provide resume text as input.

---

## 📤 Sample Output

=== Smart Resume Parser ===
👤 Name: Neha Patil
🎓 University: PES University
🏢 Companies: ['J.P. Morgan Chase & Co', 'General Electric']


---

## 📊 Observations

- ✅ NER performs well for Person and Organization extraction  
- ⚠️ University names require regex support for better accuracy  
- 🚀 Post-processing significantly improves output quality  

---

## 👩‍🎓 Author

- **Name:** Neha Rajkumar Patil  
- **SRN:** PES2UG23CS379  
- **Section:** F  

---

## 📘 Academic Context

This project was completed as part of **Unit 1 – GenAI & NLP** coursework and focuses on applying transformer-based models for analysis and extraction tasks 🎓.

---

## 📜 License

📌 This project is intended for **academic and educational use only**.
