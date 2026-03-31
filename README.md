# DeepRead Community

Welcome to the official community hub for [DeepRead](https://www.deepread.tech/).

## What is DeepRead?

DeepRead is an AI-native document processing API that turns PDFs, scans, and images into structured data with 97%+ accuracy. Using multi-model consensus (GPT + Gemini + dual OCR), it flags uncertain fields for human review instead of guessing.

**Four capabilities, one API key:**

- **OCR & Structured Extraction** — Convert any document to text or structured JSON with per-field confidence scoring. Human-in-the-loop flags tell you exactly which fields need review.
- **Form Filling** — Upload a blank PDF form + your data as JSON. AI detects fields visually, maps data semantically, fills the form, and quality-checks the result. Works on scanned, non-editable PDFs.
- **PII Redaction** — Detect and redact 14 types of PII (names, SSNs, credit cards, medical records, etc.) with irreversible black bar redaction. Context-aware: knows doctor vs patient, institutional vs personal. HIPAA/GDPR ready.
- **BYOK (Bring Your Own Key)** — Connect your own OpenAI, Google, or OpenRouter API key via the dashboard. All processing routes through your account — zero DeepRead LLM costs, page quota skipped entirely.

**Free tier:** 2,000 pages/month, no credit card required.

## Getting Started

1. Sign up at [deepread.tech/dashboard](https://www.deepread.tech/dashboard)
2. Get your API key (or use the agent device flow for automated setup)
3. Try the [demo examples](https://github.com/deepread-tech/deepread-demo) — Python, Node.js, and cURL
4. Add AI agent skills with `clawhub install uday390/deepread-ocr`

## Demo Repo

Clone and run working examples in under 60 seconds:

```bash
git clone https://github.com/deepread-tech/deepread-demo.git
cd deepread-demo
export DEEPREAD_API_KEY=sk_live_your_key
python python/01_ocr_extract.py your_document.pdf
```

Examples cover OCR extraction, structured data, form filling, PII redaction, and webhooks.

## AI Agent Skills

DeepRead works with Claude Code, Cursor, Codex, and other AI coding agents:

- **deepread-ocr** — Extract text and structured data — `clawhub install uday390/deepread-ocr`
- **deepread-form-fill** — Fill PDF forms with AI vision — `clawhub install uday390/deepread-form-fill`
- **deepread-pii** — Redact PII from documents — `clawhub install uday390/deepread-pii`
- **deepread-agent-setup** — OAuth device flow authentication — `clawhub install uday390/deepread-agent-setup`
- **deepread-byok** — Bring Your Own Key setup — `clawhub install uday390/deepread-byok`

## How to Participate

### Discussions

Use [GitHub Discussions](https://github.com/deepread-tech/deepread-community/discussions) for:
- Q&A about integration and usage
- Feature requests and ideas
- Sharing your use cases and what you've built

### Issues

Use [Issues](https://github.com/deepread-tech/deepread-community/issues) for:
- Bug reports with the API
- Documentation improvements

## Community Guidelines

1. **Be respectful** — We're all here to learn and build
2. **Search first** — Your question may already be answered
3. **Provide context** — Include code snippets, error messages, and document types when asking for help
4. **Share knowledge** — If you solve a problem, share the solution

## Resources

- [Website](https://www.deepread.tech)
- [Dashboard](https://www.deepread.tech/dashboard)
- [Demo Repo](https://github.com/deepread-tech/deepread-demo)
- [Skills Repo](https://github.com/deepread-tech/skills)
- [Discord](https://discord.com/invite/pvzMsuVM)
- [LinkedIn](https://www.linkedin.com/company/deepread-tech/)
- Email: hello@deepread.tech

## Support

- **Community support**: Post in Discussions
- **Technical issues**: Open an Issue
- **Enterprise inquiries**: hello@deepread.tech
