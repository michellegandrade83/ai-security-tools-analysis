# 🔐 AI Security Tools Analysis: Claude Code Security vs OpenAI Codex

> **A comparative analysis of AI-powered security tools for vulnerability detection**  
> *By Michelle Andrade | Cybersecurity Analyst & Content Creator*

---

## 📌 About This Project

This project analyzes and compares two leading AI security tools — **Anthropic's Claude Code Security** and **OpenAI's Codex (Aardvark)** — evaluating their effectiveness in identifying software vulnerabilities, reducing false positives, and supporting security teams in real-world scenarios.

The analysis is based on published research, official documentation, and independent testing data from Semgrep (2025/2026).

---

## 🎯 Why This Matters

AI is changing cybersecurity. The same tools that help defenders find vulnerabilities can also be used by attackers. Understanding the strengths and limitations of each platform is critical for:

- Security analysts choosing the right tool
- Companies building DevSecOps pipelines
- Compliance and governance teams assessing AI risk

---

## 📊 Key Findings

| Metric | Claude Code Security | OpenAI Codex |
|---|---|---|
| Vulnerabilities Found | 46 (in 11 apps) | 21 (in 11 apps) |
| True Positive Rate | 14% | 18% |
| False Positive Rate | 86% | 82% |
| Best at | IDOR detection (22% TPR) | Path Traversal (47% TPR) |
| SQL Injection TPR | 5% | 0% |
| XSS Detection TPR | 16% | 0% |
| Context Understanding | ✅ Strong | ⚠️ Limited |
| Consistency | ⚠️ Non-deterministic | ⚠️ Non-deterministic |
| Human Approval Required | ✅ Yes | ✅ Yes |

*Source: Semgrep Research, 2025 — tested on 11 large Python web apps (Django, Flask, FastAPI)*

---

## 📁 Project Structure

```
ai-security-tools-analysis/
│
├── README.md                  ← You are here
├── analysis/
│   └── comparison.md          ← Full written analysis
├── data/
│   └── tools_comparison.csv   ← Raw comparison data
└── references.md              ← All sources used
```

---

## 🔍 What I Analyzed

1. **Vulnerability detection rates** — How many real bugs does each tool find?
2. **False positive rates** — How much noise does each tool generate?
3. **Context understanding** — Can the tool reason about code, or just pattern-match?
4. **Consistency** — Does the tool give the same result when run twice?
5. **Governance fit** — How does each tool align with compliance frameworks (NIST, ISO 27001)?

---

## 📖 Read the Full Analysis

- 📝 [Medium Article — Claude Code Security vs OpenAI Codex](@michelle.g.andrade83)
- 📊 [Comparison Data](./data/tools_comparison.csv)
- 📋 [Full Written Analysis](./analysis/comparison.md)

---

## 🛠️ Tools & References Used

- [Semgrep Research: Finding Vulnerabilities with AI Coding Agents (2025)](https://semgrep.dev/blog/2025/finding-vulnerabilities-in-modern-web-apps-using-claude-code-and-openai-codex/)
- [Anthropic: Claude Code Security Announcement (2026)](https://www.anthropic.com/news/claude-code-security)
- [The Hacker News: Anthropic Launches Claude Code Security (2026)](https://thehackernews.com/2026/02/anthropic-launches-claude-code-security.html)
- [Security Boulevard: Thoughts on Claude Code Security (2026)](https://securityboulevard.com/2026/02/thoughts-on-claude-code-security/)

---

## 👩‍💻 About Me

I'm a cybersecurity content creator and analyst with a background in data analysis, financial services, and account management. I write about AI security tools, governance, and emerging threats.

- 📝 [Medium](@michelle.g.andrade83)
- 💼 [LinkedIn](https://www.linkedin.com/in/michelle-andrade)
- 📧 Open to opportunities in cybersecurity analysis and governance/compliance roles

---

*This project is part of my cybersecurity portfolio. All data is based on publicly available research.*
