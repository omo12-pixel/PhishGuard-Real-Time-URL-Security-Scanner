# 🛡️ PhishGuard by OmonuX
**The Future of URL Security Analysis**

Developed by **OmonuX**, this tool is designed to protect users from modern phishing threats by analyzing URL patterns, entropy, and domain risk in real-time.

## 🚀 Features
* **X-Ray Scan:** Identifies hidden redirects and suspicious keywords.
* **Risk Scoring:** Provides a percentage-based safety rating.
* **Lightweight:** Built in Python for speed and efficiency.

## 🛠️ Installation
1. `git clone https://github.com/your-repo/phishguard`
2. `pip install tldextract`
3. `python scan.py`                                                                                                                                                                                                                                  # PhishGuard: Real-Time URL Security Scanner                                                                                                                                                                                                                                                                                                      
A Python-based tool that analyzes URLs for phishing indicators, checks against blacklists, and alerts users of potential threats before they click.

## 🔍 Features
* **Entropy Check:** Detects "gibberish" or suspicious character patterns in URLs.
* **Domain Age Check:** Flags domains registered in the last 30 days (common for phishing).
* **Blacklist Integration:** Uses the Google Safe Browsing API to check known malicious links.
* **Keyword Detection:** Scans for "urgent" words like login, verify, update, paypal, bank.

## 🛠️ How it Works
The script takes a URL as input and runs multiple security checks. If the "Risk Score" is high, it warns the user.
* **Input:** `http://secure-login-paypal.com/update`
* **Output:** 🚨 **DANGER:** High Risk of Phishing detected.

## 🚀 Setup
1. Clone this repo.
2. Run `pip install tldextract`.
3. Run `python scan.py`.    
