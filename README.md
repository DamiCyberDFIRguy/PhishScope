# PhishScope

<h1>Features

- Email header parsing and analysis

- Sender spoofing detection

- URL and domain extraction

- Known-bad indicator matching

- Rule-based phishing risk scoring

- JSON incident report generation

<h2>Detection Capabilities

- Mismatch between From, Return-Path, and Received headers

- Suspicious or newly observed domains

- Obfuscated URLs (URL shorteners, hex encoding)

- IP reputation mismatches

- High-risk keyword detection in email body

<h3>Installation
git clone https://github.com/yourusername/phishscope.git
cd phishscope
pip install -r requirements.txt

</h4> Usage
python src/main.py data/sample_email.eml

<h5> Output{
  "email_subject": "Urgent: Account Verification Required",
  "risk_score": 87,
  "classification": "High Confidence Phishing",
  "indicators": {
    "domains": ["secure-login[.]co"],
    "ips": ["185.234.218.12"],
    "urls": ["http://secure-login[.]co/verify"]
  }
}
</h5>

<h6>Use Case: Incident Response Workflow

- User reports suspicious email

- Analyst uploads .eml file into PhishScope

- Tool analyzes headers and content

- Risk score determines escalation priority

- Indicators are extracted for blocking

- Incident report is attached to ticket



