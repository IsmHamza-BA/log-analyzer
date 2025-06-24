# 🛡️ Log Analyzer

A Python-based cybersecurity log analyzer that detects brute force login attempts from access logs.  
Built for hands-on security learning and real-world relevance.

---

## 🔍 Features

- Parses Apache/Nginx-style access logs
- Detects brute force attacks based on repeated 401 (unauthorized) responses
- Saves alerts as JSON reports
- Includes sample logs and modular, testable Python code

---

## 🛠️ Tech Stack

- Python 3
- Regex for log parsing
- JSON for alert storage
- Modular design (`parser.py`, `analyzer.py`, `alerting.py`)
- Flask & Matplotlib integration possible for advanced use

---

## 📁 Project Structure


---

## 🧪 How to Run

```bash
# Step 1: Clone the repo or download the files
git clone https://github.com/YOUR_USERNAME/log-analyzer.git
cd log-analyzer

# Step 2: Run the analyzer
python3 src/main.py
