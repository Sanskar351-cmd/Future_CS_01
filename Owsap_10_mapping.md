# OWASP Top 10 Mapping — Juice Shop Findings (Sanskar)

| Finding ID | Finding Title | OWASP Top 10 (2021) | Short justification |
|---|---|---|---|
| 01 | Credentials in Transit | A02 — Cryptographic Failures | Credentials visible in POST body / proxy logs |
| 02 | DOM XSS (search / feedback) | A03 — Injection (XSS) | Untrusted input executed in DOM |
| 03 | Exposed files via /ftp | A01 — Broken Access Control | Sensitive files accessible without auth |
| 04 | Chatbot coupon leakage | A01 / A05 | Business logic flaw and misconfiguration allowing coupon disclosure |
| 05 | Missing encoding / image access | A01 — Broken Access Control | Insecure direct object references for media |
| 06 | Error handling disclosure | A05 — Security Misconfiguration | Verbose error responses reveal implementation details |
