# Marc Mandel — LegalMarc

Lawyer and builder working at the intersection of **law, privacy, and local-first software**.

I build tools for professionals who handle sensitive information and need software that is useful, understandable, and trustworthy. Most of what I make is **local-first by default** — your documents stay on your machine — and ships as part of a small family of legal-tech tools I call the **Marc-\* suite**.

> The question behind most of my projects: *can this be made safer, clearer, more local, and less annoying?*

---

## 🚩 Marcut — flagship

**[Marcut](https://github.com/LegalMarc/marcut)** is an open-source, local-first document redaction tool for lawyers and professionals.

It's a native macOS app that detects and redacts confidential information and PII from Microsoft Word (`.docx`) files **without uploading anything to the cloud**. A deterministic rules engine handles structured data (SSNs, emails, phone numbers); an optional local AI engine (Ollama) catches context-dependent entities like names and organizations. Output is standard Word "Track Changes" redlines plus JSON audit and metadata-scrub reports, so a human reviews and accepts every change before anything leaves the building.

→ **[View Marcut on GitHub](https://github.com/LegalMarc/marcut)**

---

## 🧰 The Marc-\* suite

A growing set of local-first tools for legal and professional workflows.

| Tool | What it does | Status |
|------|--------------|--------|
| **Marcut** | Local-first `.docx` redaction (rules + local AI) for macOS | 🟢 Public — [repo](https://github.com/LegalMarc/marcut) |
| **Marcrypt** | Native macOS bulk PDF decryption | 🟢 Public — [repo](https://github.com/LegalMarc/Marcrypt) |
| **Marcompare** | Local-first legal document comparison & redlining for macOS | 🔒 Private |
| **Marcusign** | E-signature platform | 🔒 Private |
| **Marcabinet** | Secure document organization | 🛠️ In development |

*Private tools are listed for context; their repositories aren't publicly visible.*

---

## 🔬 Beyond legal tech

I also build for the homelab, the workshop, and everyday friction.

- **[centauri-sentinel](https://github.com/LegalMarc/centauri-sentinel)** — AI print-failure detection and alerting for the Elegoo Centauri 3D printer.
- **Skull** — a local-first AI knowledge OS (🔒 private, in active development).
- **[tab-roulette](https://github.com/LegalMarc/tab-roulette)** — a roulette wheel that declutters your tab bar, one spin at a time.
- **[apple-mail-migration](https://github.com/LegalMarc/apple-mail-migration)** — migrate Apple Mail only, when the official assistant insists on all-or-nothing.

---

## 🧭 How I build

- **Local-first** — sensitive information shouldn't travel unless it has to.
- **Auditable** — you should be able to see what the tool did and verify the result.
- **Reversible** — good systems make irreversible mistakes hard to commit by accident.
- **Human-centered** — automation supports professional judgment; it doesn't replace it.

I learn by building, testing, breaking, fixing, and documenting — drawn to the projects where the details matter: file formats, edge cases, security boundaries, and whether the thing actually works for the person who needs it.

---

## 📫 Contact

- **GitHub:** [@LegalMarc](https://github.com/LegalMarc)
- **LinkedIn:** [Marc Mandel](https://www.linkedin.com/in/marcmandel)
- **Flagship project:** [Marcut](https://github.com/LegalMarc/marcut)

<sub>LegalMarc is where I publish tools and experiments around law, privacy, automation, and local-first professional software.</sub>
