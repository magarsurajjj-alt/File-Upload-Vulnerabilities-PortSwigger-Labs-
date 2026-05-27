# File Upload Vulnerabilities – PortSwigger Labs

## Overview
This project documents my hands-on learning of file upload vulnerabilities using PortSwigger Web Security Academy.

The goal was to understand how insecure file upload mechanisms can lead to **remote code execution (RCE)** through different bypass techniques.

## Structure
file-upload-vulnerabilities/
│
├── README.md
│
├── apprentice/
│   ├── rce-web-shell-upload/
│   └── content-type-bypass/
│
├── practitioner/
│   ├── path-traversal-upload/
│   ├── extension-blacklist-bypass/
│   ├── obfuscated-extension-bypass/
│   └── polyglot-webshell/
│
├── expert/
│   └── race-condition-upload/
│
└── techniques/
    ├── bypass-cheatsheet.md
    ├── web-shells.md
    └── detection-evasion.md

### 🟢 Apprentice
- Remote code execution via web shell upload  
- Content-Type restriction bypass  

### 🟡 Practitioner
- Path traversal in file uploads  
- Extension blacklist bypass  
- Obfuscated file extension bypass  
- Polyglot web shell upload  

### 🔴 Expert
- Race condition-based file upload exploitation  

## Key Skills Learned
- File upload security testing
- Server-side validation bypass techniques
- MIME type spoofing
- Web shell creation and execution
- Race condition exploitation
- Advanced RCE techniques

## Impact
Demonstrates how insecure file upload functionality can lead to full server compromise.

## Disclaimer
All testing performed in PortSwigger Web Security Academy lab environments.
