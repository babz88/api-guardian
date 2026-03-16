# API Guardian

API Guardian is an automated API security scanner built in Python.

It detects common API vulnerabilities including:

- SQL Injection
- Authentication Bypass
- Missing Rate Limiting
- Exposed Endpoints

## Features

- Automatic endpoint discovery
- SQL injection testing
- Authentication bypass detection
- Rate limit vulnerability testing
- Security score generation
- HTML security report

## Installation

git clone https://github.com/yourusername/api-guardian.git

cd api-guardian

pip install -r requirements.txt

## Usage

python api_guardian.py https://api.example.com

## Example Output

Endpoints Scanned: 6  
Vulnerabilities Found: 1  

Security Score: 92/100

## Technologies Used

Python  
Requests  
Pandas  

## Security Inspiration

This tool takes inspiration from modern security testing approaches used by tools like Burp Suite and OWASP ZAP.
