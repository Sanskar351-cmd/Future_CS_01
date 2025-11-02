# OWASP Juice Shop — Security Assessment (Sanskar, Future Interns)

## Summary
Local security assessment of OWASP Juice Shop (http://localhost:3000) performed as part of the Future Interns program.
Report author: Sanskar
Date: 2025-11-01

## What's included
- `final_report/` — Polished PDF report (OWASP_Juice_Shop_Security_Assessment_Report_Sanskar_Future_Interns.pdf)
- `findings/` — One-page Markdown findings (detailed PoC, remediation, redaction notes)
- `evidence/screenshots/` — Screenshots (REDACT: remove/blur plaintext credentials)
- `evidence/logs/` — Raw scanner outputs (Burp export, dirb output, zap report if available)
- `appendix/` — Payloads & OWASP mapping

## Authorization / Scope
Testing was performed on a local OWASP Juice Shop instance for educational purposes only. No external or production systems were tested.

## How to use this repo
1. Review `final_report/` for the executive summary and full narrative.
2. Open `findings/` for step-by-step PoCs (includes payloads & redaction placeholders).
3. Evidence is in `evidence/` — do not publish unredacted screenshots publicly.

## Important: Redaction
Before publishing publicly, ensure you have redacted passwords/session tokens visible in screenshots:
- `evidence/screenshots/burp_login_post.png` → redact the password/email shown in the POST body.
- `evidence/screenshots/burp_error_response.png` → redact stack traces or tokens if needed.

## Contact
Prepared by: Sanskar — Future Interns
