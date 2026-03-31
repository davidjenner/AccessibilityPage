# OpenDyslexic Text Converter

> A free, browser-based accessibility tool that converts any text into the [OpenDyslexic](https://opendyslexic.org/) font — designed to improve readability and reduce reading errors for people with dyslexia.

---

## Live Demo

**[Try it now →](https://davidjenner.github.io/AccessibilityPage/)**

---

## What It Does

Paste or type any text — from a website, email, document, or anywhere else — and instantly render it in the OpenDyslexic typeface. A suite of additional accessibility controls lets you fine-tune the experience to suit your needs.

| Feature | Description |
|---|---|
| **OpenDyslexic Font** | Converts any input text to the OpenDyslexic typeface |
| **Paste from Clipboard** | One-click paste directly from your clipboard |
| **Pastel Mode** | Switches to a soft warm background to reduce visual stress |
| **High Contrast Mode** | Black background with yellow text for maximum contrast |
| **Text Size Controls** | Incrementally increase or decrease the output font size |
| **Read Aloud** | Uses the Web Speech API to read the converted text aloud |
| **Copy Output** | Copy the rendered text back to your clipboard instantly |

---

## Screenshots

> *(Add screenshots here once hosted — recommended: default view, pastel mode, high contrast mode)*

---

## Why OpenDyslexic?

[OpenDyslexic](https://opendyslexic.org/) is a free typeface created by Abelardo Gonzalez. Each letter has a unique shape and a weighted bottom, which helps anchor letters and reduce the letter-flipping and swapping that some people with dyslexia experience. While research on its effectiveness is ongoing, many users report a meaningful improvement in reading comfort.

---

## Tech Stack

- **HTML5** — semantic, accessible markup
- **CSS3** — custom properties, responsive grid layout
- **Vanilla JavaScript** — no frameworks or build steps required
- **Web Speech API** — native browser text-to-speech
- **OpenDyslexic font** — served locally via `@font-face`
- **Font Awesome 6** — iconography
- **Google Fonts (Inter)** — UI typography

---

## Getting Started

No install needed. Just open `index.html` in any modern browser.

```bash
git clone https://github.com/davidjenner/AccessibilityPage.git
cd AccessibilityPage
# Open index.html directly, or serve locally:
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

---

## Other Projects by David Jenner

| Project | Description |
|---|---|
| [TimeBox ADHD](https://timeboxadhd.netlify.app/) | A time-boxing productivity tool designed for people with ADHD |
| [Outseek](https://outseek.davidjenner.workers.dev/) | Fast, minimal search tool built on Cloudflare Workers |

---

## Feedback & Issues

Found a bug or have a feature request? [Open an issue on GitHub](https://github.com/davidjenner/AccessibilityPage/issues) — all feedback is welcome.

---

## Credits & Attributions

- **[OpenDyslexic](https://opendyslexic.org/)** font by [Abelardo Gonzalez](https://github.com/antijingoist/opendyslexic) — licensed under [SIL Open Font License](https://openfontlicense.org/)
- **[Font Awesome](https://fontawesome.com/)** — icons licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
- **[Inter](https://rsms.me/inter/)** typeface by Rasmus Andersson — licensed under [SIL Open Font License](https://openfontlicense.org/)
- **[Buy Me a Coffee](https://www.buymeacoffee.com/godavid)** — support widget

---

## Support

If this tool has been useful to you, consider [buying me a coffee](https://www.buymeacoffee.com/godavid). It helps keep projects like this free and maintained.

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-FF813F?style=for-the-badge&logo=buy-me-a-coffee&logoColor=white)](https://www.buymeacoffee.com/godavid)

---

## Licence

This project is open source under the [MIT Licence](LICENSE).

---

*Built with accessibility in mind by [David Jenner](https://github.com/davidjenner) &copy; 2026*
