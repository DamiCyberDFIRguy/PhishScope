# PhishScope

Features

Email header parsing and analysis

Sender spoofing detection

URL and domain extraction

Known-bad indicator matching

Rule-based phishing risk scoring

JSON incident report generation

Detection Capabilities

Mismatch between From, Return-Path, and Received headers

Suspicious or newly observed domains

Obfuscated URLs (URL shorteners, hex encoding)

IP reputation mismatches

High-risk keyword detection in email body

Installation
git clone https://github.com/yourusername/phishscope.git
cd phishscope
pip install -r requirements.txt

python src/main.py data/sample_email.eml

