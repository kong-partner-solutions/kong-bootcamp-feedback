# Contributing to Kong Bootcamp Feedback

Thank you for contributing to the **Kong Enablement Bootcamp Learning Ecosystem**!
Your feedback, bug reports, and suggestions help ensure our hands-on labs and enablement materials remain best-in-class for partners and architects worldwide.

---

## 📬 How to Submit Feedback

### 1. In-Page Feedback Widget (Fastest)
At the bottom of every lab and documentation page across the bootcamps on [https://bootcamp.kong-demo.com](https://bootcamp.kong-demo.com), you will find a **"Was this page helpful?"** widget:
- Click **👍 Yes** or **👎 Needs Improvement**
- Click **💬 Partner Feedback** to open a pre-populated issue directly linked to that specific lab URL and module.

### 2. GitHub Issues
You can also open an issue directly in this repository:
- **🐛 [Bug Report](https://github.com/kong-partner-solutions/kong-bootcamp-feedback/issues/new?template=02_broken_lab.yml)**: If a command failed, a container won't start, or a decK syntax error occurred.
- **💬 [Page Feedback](https://github.com/kong-partner-solutions/kong-bootcamp-feedback/issues/new?template=01_page_feedback.yml)**: If instructions are unclear, missing context, or have typos.
- **💡 [Lab / Topic Proposal](https://github.com/kong-partner-solutions/kong-bootcamp-feedback/issues/new?template=03_topic_request.yml)**: If you would like to see a new architecture pattern, plugin, or exam scenario added.

---

## 🔒 Confidentiality & Security Rules

> [!CAUTION]
> **NEVER submit sensitive credentials or tokens in public issues!**
> - Do **not** post Kong Konnect Personal Access Tokens (`kpat_...`)
> - Do **not** post Keycloak client secrets, private keys, or passwords
> - Do **not** post proprietary enterprise URLs or production API keys
> - Always sanitize terminal logs by replacing real secrets with `<YOUR_KONNECT_TOKEN>` or `<REDACTED>` before submitting.

If you believe you have discovered a security vulnerability in Kong Gateway or Konnect, please refer to our [Security Policy](SECURITY.md).

---

## 🛠️ Triaging & SLA

1. **Automated Triage**: Our GitHub Actions workflow automatically labels issues with the target bootcamp track.
2. **Review**: The Kong Partner Solutions and Enablement team reviews incoming issues on a continuous basis.
3. **Agent Remediation**: Issues with `<!-- agent-metadata ... -->` blocks are ingested into our autonomous remediation pipeline to rapidly push documentation and manifest fixes to the live learning portal.
