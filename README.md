# 🛡️ CyberShield Pro — AI Cyber Threat Analyzer

This repository focuses on the application of Artificial Intelligence (AI) in the field of Cybersecurity. It explores how intelligent systems can be used to detect, prevent, and respond to cyber threats effectively.
The goal of this repository is to provide a structured understanding of how AI techniques enhance modern security systems.
---

## 📁 Project Structure

```
ai_threat_dashboard/
├── app.py                  ← Flask backend (ML logic + API routes)
├── requirements.txt        ← Python dependencies
├── threat_logs.csv         ← Auto-generated scan log (created on first run)
├── templates/
│   └── index.html          ← Professional dashboard UI
├── data/
│   ├── phishing_site_urls.csv
│   ├── synthetic_malware_url_dataset.csv
│   └── cybersecurity_intrusion_data.csv
└── models/                 ← Saved ML models (auto-created)
```

---

## 🚀 How to Run

### Step 1 — Install Python (if not installed)
Download from: https://python.org (Python 3.8+ required)

### Step 2 — Open Terminal / Command Prompt
Navigate to the project folder:
```bash
cd ai_threat_dashboard
```

### Step 3 — Install Dependencies
```bash
pip install -r requirements.txt
```

### Step 4 — Run the App
```bash
python app.py
```

### Step 5 — Open Browser
Go to: **http://127.0.0.1:5000**

---

## 🧪 What You Can Analyze

| Input Type   | Example                                              |
|-------------|------------------------------------------------------|
| URL          | `http://login-verify-bank.secure.xyz/auth`          |
| Email        | `attacker@secure-login-update.com`                  |
| Safe URL     | `https://google.com`                                |
| File         | `malware.exe` or `C:/downloads/setup.bat`           |
| Brute Force  | `Multiple failed SSH login attempts from 192.168.1.1` |
| DDoS         | `UDP flood packet storm amplification attack`       |

---

## 📊 Dashboard Features

- **4 Metric Cards** — Total, Malicious, Safe, Avg Score
- **Threat Donut Chart** — Safe vs Malicious breakdown
- **Attack Type Bar Chart** — Which input types appear most
- **Severity Gauge** — System-wide risk level (0–100%)
- **Probability Histogram** — Distribution of all threat scores
- **Trend Line Chart** — Threat score over last 20 scans
- **Scan Logs Table** — Last 10 entries with timestamps

---

## 🛠️ Technologies Used

- **Backend:** Python, Flask
- **ML:** scikit-learn (Random Forest, TF-IDF)
- **Frontend:** HTML5, CSS3, JavaScript (no React/npm needed)
- **Charts:** Chart.js (CDN)
- **Fonts:** Google Fonts (Space Mono + Syne)

---

## ⚡ Notes

- No internet required after first load (Chart.js loads from CDN once)
- Models are trained automatically from your CSV datasets on first run
- All scan results are saved to `threat_logs.csv`
