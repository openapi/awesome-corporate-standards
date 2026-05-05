# Contributing to awesome-corporate-standards

Thank you for taking the time to contribute! This guide explains how to add or update entries.

## What belongs in this list

This list is exclusively for standards, frameworks, and certifications that apply to **organizations, companies, and processes** — not to individuals.

**In scope:**
- ISO, IEC, and national standards certifiable by organizations (ISO 9001, ISO 27001, ISO 14001, etc.)
- Regulatory frameworks that organizations must comply with (GDPR, SOX, PCI DSS, etc.)
- Industry-specific quality or safety standards (IATF 16949, AS9100, ISO 13485, etc.)
- GRC frameworks (COBIT, COSO, ISO 31000, etc.)

**Out of scope:**
- Personal/professional certifications (AWS Certified, PMP, CISSP, CISM, etc.) → see [awesome-certificates](https://github.com/PanXProject/awesome-certificates)
- Developer tools, SDKs, libraries
- Company-proprietary methodologies without a recognized certification body

## How to add an entry

1. **Fork** the repository and create a branch: `git checkout -b add/iso-XXXXX`
2. **Edit** the appropriate `README.md` (and translations if you can)
3. **Follow the format:**

```markdown
- **[STANDARD NAME](https://official-body-url.org/)** — One or two sentences: what does it certify, why does it matter, who is it for.
```

4. **Place it** in the correct section. If no section fits, open an issue to discuss adding one.
5. **Open a Pull Request** with a clear title and description.

## Entry quality guidelines

- Link to the **official issuing body** (ISO, NIST, AICPA, etc.), not Wikipedia or third-party summaries.
- Description must explain **what the standard certifies** and **why an organization would pursue it**.
- Do not duplicate entries already present — check all sections and translations.
- Keep descriptions neutral and factual. No marketing language.

## Translations

The list is maintained in four languages:

| File | Language |
|------|----------|
| `README.md` | English (canonical) |
| `README.it.md` | Italian |
| `README.de.md` | German |
| `README.es.md` | Spanish |

When adding a new entry, update the English version first. If you can provide the translation(s), add them too — otherwise note it in the PR and a maintainer will handle it.

## Reporting issues

- **Broken link** → open an issue with the URL and the correct replacement.
- **Outdated information** → open an issue or a PR with the correction and a source.
- **Missing standard** → open an issue describing the standard and why it belongs here before submitting a PR.

## Code of Conduct

Be respectful and constructive. Contributions are reviewed by maintainers and may be edited for clarity, consistency, or scope.

---

Thank you for helping keep this list accurate and useful!