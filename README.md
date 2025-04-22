# 📚 Quote Scraper – Master Bundle (v4 Rebuilt Enhanced Fixed)

This project is a fully-featured Python application for scraping **famous quotations** from verified public domain sources (like Wikiquote, Project Gutenberg, Bartleby, and the Library of Congress).

The application supports:
- ✅ Streamlit and Flask web interfaces
- ✅ Export to CSV, Excel, SQLite, MySQL
- ✅ Public domain filtering
- ✅ NLP quote detection with regex + spaCy
- ✅ Documentation with embedded visuals
- ✅ Fully local Windows 11 support and .bat launcher

---

## 📦 What's Included

```
Quote_Scraper_Master_Bundle/
├── docs/                       # 📄 User & Developer Guides (.docx)
├── scripts/                    # ⚙️ Launcher, Reset Script, MySQL Config
├── examples/                   # 📊 CSV, DOCX, and PDF quote samples
├── tools/                      # 📦 App, Merge Tools, and UI Theme ZIPs
├── LICENSE.txt
├── CREDITS.md
└── requirements.txt            # 🧰 Python dependencies
```

---

## 🚀 How to Run

### 🖥️ Windows 11:
1. Install Python 3.9+
2. Unzip the bundle
3. Double-click `master_launcher.bat` to launch Streamlit or Flask interface

### 🌐 Web (Cross-platform):
```bash
# For Streamlit
streamlit run streamlit_app.py

# For Flask
python flask_app/app.py
```

Visit:
- http://localhost:8501 for Streamlit
- http://localhost:5000 for Flask

---

## 💾 Features

- Search by Theme, Author, Date
- Choose "Public Domain Only" to filter results
- NLP filtering: regex, spaCy, sentence parsing
- Export buttons for Excel, CSV, and database
- Developer tools and CLI support
- Merge quotes into DOCX journal or generate KDP-formatted output

---

## 📚 Documentation

All `.docx` files inside the `docs/` folder include:
- Step-by-step user and developer guides
- Windows 11 and Web setup walkthroughs
- PNG visuals embedded into each guide

---

## ✅ Requirements

```bash
pip install -r requirements.txt
```

Dependencies:
- Python 3.9+
- pandas
- streamlit
- flask
- spacy
- openpyxl
- python-docx
- fpdf

---

## 📜 License

MIT License – See `LICENSE.txt`  
Credits listed in `CREDITS.md`

---

## ✨ Author

Created and maintained by [@eeelisberg](https://github.com/eeelisberg)
