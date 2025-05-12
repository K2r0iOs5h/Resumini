
# 📄 Resumini

**Resumini** is a smart, lightweight resume screening tool built using Python. It uses Natural Language Processing (NLP) and Machine Learning techniques to match resumes with a given job description and ranks candidates based on relevance.

---

## 🚀 Features

* 📂 Upload a folder of resumes (`.pdf` or `.docx`)
* 📜 Input a job description file (`jd.txt`)
* 🤖 Uses TF-IDF and cosine similarity for ranking
* 📊 Displays matching scores in a table
* 💾 Saves results to `results.csv`
* 🖥️ Terminal-based GUI with progress spinners and menu options

---

## 🛠️ Technologies Used

* Python
* `scikit-learn`
* `pandas`
* `PyPDF2`
* `docx2txt`
* `rich` (for terminal GUI)

---

## 📁 Folder Structure

```
project-root/
│
├── resume.py           # Main script
├── jd.txt              # Job description file
├── resumes/            # Folder with candidate resumes
├── results.csv         # Output file with ranked results
└── README.md           # This file
```

---

## ⚙️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/resumini.git
cd resumini
```

### 2. Create and Activate a Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate  # On Windows
source venv/bin/activate  # On macOS/Linux
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

> If `docx2txt` fails, try reinstalling manually: `pip install docx2txt`

### 4. Prepare Inputs

* Place your **job description** in `jd.txt`
* Add resumes (PDF or DOCX) inside the `resumes/` folder

### 5. Run the Tool

```bash
python resume.py
```

---

## 🧠 Sample Output

```
📊 Resume Match Results
┏━━━━━━━━━━━━━━━━┳━━━━━━━━━━━┓
┃ Resume         ┃ Match (%) ┃
┡━━━━━━━━━━━━━━━━╇━━━━━━━━━━━┩
│ john_doe.pdf   │    30.95% │
│ jane_smith.pdf │    23.04% │
└────────────────┴───────────┘
✅ Results saved to results.csv
```

---

## 💡 Inspiration

This tool is lovingly named after **Harini** 💖 — blending tech and heart. Resumini simplifies resume screening for recruiters, HR teams, and startups.

