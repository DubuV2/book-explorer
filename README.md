# Book Explorer

A Streamlit web app that scrapes data from https://books.toscrape.com
and lets you explore it interactively with filters, charts, and exports.
This project is built for learning and training purposes.

---

## Demo
<p align="center">
  <img src="assets/demo.gif" width="450">
  <img src="assets/demo_filter.png" width="200">
</p>

<p align="center">
  <img src="assets/demo_data.png" width="600">
</p>

---

## Features

- Multi-threaded scraping and multi-page architecture.
- Real-Time Feedback: Live progress bar and detailed logs.
- Data Persistence: Option to save raw results in CSV, JSON, or SQLite formats.
- Exploration: Filter and analyze results by Category, Price, and Rating.
- Export: Ability to export the filtered dataset as CSV file.
- Developer Mode: Access to advanced settings and a direct database view.

---

## Setup and Installation
You can run this app **locally** or **online**.

---

### Option 1 — Local Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/DubuV2/scraping
   cd book-explorer
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application**
   ```bash
   streamlit run src/app.py
   ```

Then open:  
```
http://localhost:8501
```

---

### Option 2 — Online (Streamlit Cloud)
Run the app directly here:

**Live App:**  
https://scraping-nrnbnzwskobmfwk3ffnmdj.streamlit.app/

---


## Data Output

By default, scraped data is saved in the `data/` folder:

- `data/books.csv`  
- `data/books.json`  
- `data/books.db`  

> You can change the output path directly from the app interface.

---

## Author 

Developed by **Doufu (DubuV2)** - 2025
Built using **Python** and **Streamlit**
