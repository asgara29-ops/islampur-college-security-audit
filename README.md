# Islampur College - Passive Security Audit
**Auditor:** Md Asgar | Siliguri, West Bengal  
**Date:** 09 Oct 2026  
**Target:** islampurcollege.ac.in (217.21.95.248)  
**Type:** Passive Recon - 100% Legal, No Intrusion

## 🛠️ Tools Used
- Qualys SSL Labs
- securityheaders.com
- crt.sh
- DNSChecker.org

## 🔍 Findings

### 1. SSL/TLS - GRADE A (Strong)
- TLS 1.3 + PQC Supported
- EC 256 bits Cert Valid till Dec 2026
- Minor: 3 Weak CBC ciphers enabled

### 2. Security Headers - GRADE D
- Missing: HSTS, X-Frame-Options, X-Content-Type-Options
- Risk: Clickjacking (Low)

### 3. Subdomain Recon
- Found: mail, cpanel, webmail via crt.sh
- Status: No A Record - Disabled (GOOD)

## ✅ Verdict: 75/100 - GOOD but improvable

### Fix
