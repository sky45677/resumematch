# Security Policy

## 🛡️ PII Data Protection
ResumeMatch AI processes highly sensitive data (Names, Phone numbers, Emails). 
- **No Data Persistence**: Resumes are processed in-memory or stored temporarily for session duration.
- **Encryption**: All database connections utilize SSL/TLS.
- **API Keys**: Secrets are never committed to version control; use `.env` files.

## 🐛 Reporting Vulnerabilities
If you discover a security vulnerability, please **do not** open a public issue. Instead:
1. Email the maintainer at `your-email@example.com`.
2. Provide a detailed description of the exploit.
3. Include a Proof of Concept (PoC) if possible.

We will acknowledge reports within 48 hours and provide a timeline for the fix.
