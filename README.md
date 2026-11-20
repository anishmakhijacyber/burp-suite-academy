# Burp Suite Academy Notes

Personal notes and lab write-ups for PortSwigger Web Security Academy, organized by topic. Each solution should explain the vulnerability, how it was identified, and the key learning points.

> These notes are for learning in PortSwigger Web Security Academy labs and other environments where testing is explicitly authorized. Do not use techniques against systems without permission.

## Repository structure

- [`notes/`](notes/) — Burp Suite features, testing methodology, and concise topic references.
- [`labs/`](labs/) — Lab write-ups grouped by vulnerability topic.
- [`resources/`](resources/) — Checklists, payload references, and useful links.

## Lab write-up format

For each lab, include:

1. **Lab** — title and Academy link.
2. **Topic and difficulty** — as listed by the Academy.
3. **Objective** — what needs to be achieved.
4. **Recon and observations** — relevant requests, responses, and behavior.
5. **Steps** — a clear, reproducible solution. Redact session cookies, tokens, and personal data.
6. **Why it works** — the underlying weakness.
7. **Takeaways and defenses** — what to remember and how to prevent it.

## Topics

Add a folder under `labs/` for each topic as notes grow. Suggested topics include SQL injection, authentication, access control, path traversal, file upload, command injection, business logic, information disclosure, SSRF, XXE, XSS, CSRF, clickjacking, DOM-based vulnerabilities, and API testing.

## Disclaimer

This repository is a personal study resource. Lab solutions are provided for educational purposes; follow PortSwigger Academy rules and applicable laws.
