# SME‑CRAF

SME‑CRAF (SME Cybersecurity Risk Assessment Framework) is a lightweight, five‑phase risk assessment approach designed for small and medium‑sized enterprises (SMEs). It focuses on making structured cyber‑risk management practical for organisations with limited time, budget and specialist staff.

## Project overview

The framework guides users through:
1. Scoping (business context and assets in scope)
2. Asset identification
3. Risk identification (threats, vulnerabilities, existing controls)
4. Risk evaluation (1–5 likelihood × impact, colour‑coded bands, prioritised register)
5. Treatment planning and monitoring

A browser‑based prototype, built with HTML, CSS and vanilla JavaScript, implements these phases and stores state in simple in‑memory structures. It calculates risk scores, assigns bands, and produces an asset register, risk register and treatment plan.

## AI‑assisted remediation

The prototype integrates large language model APIs (for example Google Gemini and Anthropic Claude) to generate context‑aware remediation suggestions based on the SME’s sector, size, assets, threats and existing controls. Basic fallback logic provides pre‑written suggestions if the API is unavailable.

## Status

This prototype was developed as part of my final‑year BSc Cybersecurity & Digital Forensics project at Middlesex University Mauritius. The framework and tool were evaluated using functional tests and an anonymous questionnaire of participants with cybersecurity / IT knowledge.
