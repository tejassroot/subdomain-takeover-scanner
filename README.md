# Subdomain Takeover Scanner

Python-based strict subdomain takeover detection framework focused on minimizing false positives through DNS validation, HTTP fingerprinting, SSL verification, and claimability checks.

## Features

- DNS Validation
- HTTP Fingerprinting
- SSL Verification
- False Positive Filtering
- Multi-threaded Scanning
- JSON Export

## Requirements

- Python 3
- dnspython
- requests
- urllib3

## Installation

```bash
git clone https://github.com/tejassroot/subdomain-takeover-scanner.git
cd subdomain-takeover-scanner

pip install -r requirements.txt
chmod +x takeoverpossible
```

## Usage

### Single Domain

```bash
./takeoverpossible -d sub.example.com
```

### Multiple Domains

```bash
./takeoverpossible -f domains.txt
```

### Export JSON

```bash
./takeoverpossible -f domains.txt -o results.json
```

## Disclaimer

This tool is intended for authorized security testing and bug bounty programs only.
