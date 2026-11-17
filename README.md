# Psychelog — Encrypted Integration Journal for the Days Around a Session

**Where insight becomes integration. A private, encrypted companion for the days around a session: follow a guided plan, capture what you feel, hear your own patterns and carry the meaning into daily life.**

[![Live App](https://img.shields.io/badge/Live%20App-psychelog.lyfmail.com-teal)](https://psychelog.lyfmail.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-purple.svg)](https://github.com/lyfmail-official/psychelog/blob/main/LICENSE)
[![PWA](https://img.shields.io/badge/PWA-Offline--First-orange.svg)](https://psychelog.lyfmail.com)
[![Privacy](https://img.shields.io/badge/Privacy-Zero%20Tracking%20%C2%B7%20No%20Cookies-green.svg)](https://psychelog.lyfmail.com)
[![Maintained by LYF Mail](https://img.shields.io/badge/Maintained%20by-LYF%20Mail-red)](https://lyfmail.com)

A free project from [LYF Mail](https://lyfmail.com) — India's privacy-first digital wellness platform.

---

## 📓 What Is Psychelog?

**Psychelog** (PsycheLog) is a **private, encrypted integration journal** and **local-first companion for the days around a session**. Follow a guided weekly plan, capture what you feel, hear your own patterns and carry the meaning into daily life. **Nothing leaves your device unless you decide.**

**AES-256 encrypted · Works offline · No accounts · English and हिन्दी · Zero tracking, no cookies, no database.**

Built by [LYF Mail](https://lyfmail.com), a [privacy-first digital wellness platform](https://lyfmail.com) serving 50,000+ subscribers across India since 2020.

> Psychelog is a journal, **not medical care**. See the in-app safety notice.

---

## 🧭 How It Works — A Private Integration Loop

No feeds, no profiles, no servers holding your story. Just a calm, structured loop:

1. **🧭 Prepare** — a six-point safety checklist, a written or spoken intention and your emergency contacts in one tap. Nothing starts until you have confirmed your context is safe, supported and lawful.
2. **🌀 Stay Present** — session mode keeps a gentle timer, marks phases you choose, offers 4-7-8, box and coherent breathing, prompts a check-in every 20 minutes and captures notes or voice memos with a press.
3. **🌱 Integrate** — turn the session into a journal entry prefilled with your notes. Over time, on-device insights show tone, emotions and recurring themes, so reflection becomes action.

---

## 📅 Guided Plan — Six Weeks to Carry the Insight Home

Each week brings one theme, one gentle practice and a few reflection prompts. Every answer becomes a private, encrypted journal entry, and a weekly check-in tracks how you feel.

| Week | Theme |
|------|-------|
| 1 | Settle & Ground |
| 2 | Name the Insights |
| 3 | Meet the Hard Parts |
| 4 | Values & Direction |
| 5 | Relationships & Boundaries |
| 6 | Anchor & Look Ahead |

A softer **4-week "Gentle Grounding" plan** is included for times when things feel unsettled. Add a weekly reminder to your own calendar with one tap. No notifications, no servers.

---

## ✨ Key Features

- 🔐 **AES-256-GCM Vault** — text, tags, notes, contacts and audio are encrypted before they touch storage. The key is non-extractable and lives only in memory while unlocked.
- 🧂 **PBKDF2 Key Derivation** — 310,000 iterations of PBKDF2-HMAC-SHA256 with a random salt slow down password guessing, and the vault throttles repeated failures.
- 📴 **Offline-First PWA** — install it like an app. A service worker caches the interface so you can journal with no connection at all.
- 🧠 **On-Device Insights** — sentiment, emotions and themes are computed locally with a built-in lexicon. No AI service ever receives your words.
- 🎙️ **Encrypted Voice Memos** — recorded with the same key, played back only after you unlock.
- 🗃️ **No Database, Zero-Knowledge Sync** — the site has no database. Optional sync stores one opaque encrypted file that the server cannot read or search.
- 🔑 **Optional Passkey Unlock** — unlock with fingerprint, face or a security key. Your password stays the master key; the passkey only unwraps a copy on your device.
- 📄 **Therapist Export (CSV and PDF)** — choose a date range and share a spreadsheet or a tidy PDF summary. Voice memos are never included.
- 🌐 **English, हिन्दी and Local Help** — switch the whole interface between English and Hindi, and see crisis lines for your own country automatically.

---

## 🧬 Core Principles — Reflection, Not Surveillance

**We never:** ask for your name, email, phone number or any identity · send your writing, recordings or metadata to our server unless you turn on sync · run analytics, ads, fingerprinting or third-party trackers · recommend doses, sources or substances · use your words to train models or build profiles · keep a back door or a recovery key to your vault.

**We always:** encrypt in your browser before anything is saved · put an Emergency button and grounding tools one tap away · work offline and let you export everything you own · let you erase all data from your device in seconds · keep the code readable (plain HTML, CSS and JavaScript, no build step) · say plainly that this is a journal, not medical care.

---

## 🆘 You Are Not Alone

If you are in distress or in danger, **reach out to a person now**. Psychelog shows free helplines for the country you choose. In India, **Tele-MANAS is free on 14416**. If you are in immediate danger, contact local emergency services.

---

## 🚀 Quick Start Guide

### For Users
1. **Visit** [psychelog.lyfmail.com](https://psychelog.lyfmail.com) and choose **Create Your Vault**.
2. **Set a strong password.** There is **no recovery by design**, so keep it safe or use an encrypted backup file you control.
3. **Prepare, stay present, integrate**, then follow the six-week plan.
4. **Install** it to your home screen for the calmest experience.

### For Developers
```bash
git clone https://github.com/lyfmail-official/psychelog.git
cd psychelog
python -m http.server 8080   # or: npx serve .
```
Open `http://localhost:8080`. The code is plain HTML, CSS and JavaScript with no build step. See [`CONTRIBUTING.md`](CONTRIBUTING.md).

---

## 🌍 Who Uses Psychelog?

### 🏥 Clinical & Licensed Programmes
Participants in trials and licensed programmes can keep a private record to discuss with their care team, with a backup file they control and can share on their terms.

### 🛋️ Integration Therapy
Bring structured notes, voice memos and mood trends to your therapist or integration coach. Writing between appointments keeps insights from fading.

### 🌿 Self-Guided Reflection
Daily prompts, body-awareness cues and grounding tools help you process experiences gently, at your own pace, without anyone watching.

### 📈 Long-Term Growth
Streaks, sentiment lines and pattern counts reveal what changes over weeks and months, including how sleep and heart-rate variability relate to the tone of your writing.

---

## 🤝 Contributing to Psychelog

Psychelog welcomes contributions that respect our core principles:

- **Encrypt in the browser** — everything is encrypted before it is saved.
- **No back door** — never add a recovery key or master override for the vault.
- **Never recommend substances** — do not add dosing, sourcing or substance advice.
- **Safety first** — keep the Emergency button and grounding tools one tap away, and keep the journal-not-medical-care message clear.
- **Privacy-first** — never introduce tracking, analytics or unnecessary data collection.
- **Accessibility-first** — every feature must work for users with disabilities.

Please read [`CONTRIBUTING.md`](CONTRIBUTING.md) and [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) before submitting pull requests. To report a vulnerability, see [`SECURITY.md`](SECURITY.md).

---

## 🏗️ The LYF Mail Ecosystem

Psychelog is one of **fifteen free privacy-first apps** built by [LYF Mail](https://lyfmail.com), a [digital wellness platform](https://lyfmail.com) from Varanasi, India, serving 50,000+ subscribers since 2020. Browse them all at [lyfmail.com/privacy-first-apps](https://lyfmail.com/privacy-first-apps), or explore our other projects:

| Project | Description | Live App | Repository |
|---------|-------------|----------|------------|
| **[LYF Mail](https://lyfmail.com)** | Privacy-first newsletters for health, wealth, career & mindfulness. | [lyfmail.com](https://lyfmail.com) | `lyfmail` |
| **[LYF Mail App](https://app.lyfmail.com)** | Installable app with newsletters, guides and free tools. | [app.lyfmail.com](https://app.lyfmail.com) | `lyfmail-pwa` |
| **[Ebb](https://ebb.lyfmail.com)** | Private period and fertility tracker. Data stays on your device. | [ebb.lyfmail.com](https://ebb.lyfmail.com) | `ebb` |
| **[Together](https://together.lyfmail.com)** | Silent shared presence for calm. No feed, no likes, no chat. | [together.lyfmail.com](https://together.lyfmail.com) | `together` |
| **[Rewriter](https://rewriter.lyfmail.com)** | Private narrative therapy writing companion with six guided phases. | [rewriter.lyfmail.com](https://rewriter.lyfmail.com) | `rewriter` |
| **[Offload](https://offload.lyfmail.com)** | Pre-sleep brain dump with pink noise, optional binaural beats and a dream journal. | [offload.lyfmail.com](https://offload.lyfmail.com) | `offload` |
| **[Mnemo](https://mnemo.lyfmail.com)** | Private encrypted second brain with on-device AI search and chat. | [mnemo.lyfmail.com](https://mnemo.lyfmail.com) | `mnemo` |
| **[Fitrail](https://fitrail.lyfmail.com)** | Encrypted fitness, sleep and workout tracker with route privacy. | [fitrail.lyfmail.com](https://fitrail.lyfmail.com) | `fitrail` |
| **[TrustLens](https://trustlens.lyfmail.com)** | Check news, links and forwarded messages for misinformation before you share. | [trustlens.lyfmail.com](https://trustlens.lyfmail.com) | `trustlens` |
| **[LYF SOS](https://lyfsos.lyfmail.com)** | Offline emergency mesh network for Android. Built for India. | [lyfsos.lyfmail.com](https://lyfsos.lyfmail.com) | `lyfsos` |
| **[PDPR](https://pdpr.lyfmail.com)** | Public Dark-Pattern Registry. Document deceptive UX ethically. | [pdpr.lyfmail.com](https://pdpr.lyfmail.com) | `pdpr` |
| **[Signals](https://signals.lyfmail.com)** | Privacy-first analytics. Human vs. bot detection without cookies or fingerprinting. | [signals.lyfmail.com](https://signals.lyfmail.com) | `signals` |
| **[Custos](https://custos.lyfmail.com)** | Local-first guardian for sensitive financial data before it reaches AI. | [custos.lyfmail.com](https://custos.lyfmail.com) | `custos` |
| **[HireStack](https://hirestack.lyfmail.com)** | Nine free career tools for freelancers and job seekers. Works offline. | [hirestack.lyfmail.com](https://hirestack.lyfmail.com) | `hirestack` |
| **[Veilora](https://veilora.lyfmail.com)** | Six free tools for creators: clean image metadata, scan text, check before publishing. | [veilora.lyfmail.com](https://veilora.lyfmail.com) | `veilora` |

### 📚 Free Newsletters & Guides
- [Health & Wellness Guide](https://lyfmail.com/health-wellness-guide)
- [Personal Finance Guide](https://lyfmail.com/personal-finance-guide)
- [Career Development Guide](https://lyfmail.com/career-development-guide)
- [Creativity Resources](https://lyfmail.com/creativity-resources)
- [Mindfulness Practices](https://lyfmail.com/mindfulness-practices)

**Newsletter Signups:** [Health](https://health.signup.lyfmail.com) · [Finance](https://financing.signup.lyfmail.com) · [Career](https://career.signup.lyfmail.com) · [Creativity](https://creativity.signup.lyfmail.com) · [Personal Development](https://intuition.signup.lyfmail.com)

---

## 📜 License

Psychelog is released under the **MIT License**. You are free to use, modify and distribute it — including commercially. See [`LICENSE`](LICENSE) for full terms.

---

## 📫 Connect With Us

- **🌐 Website:** [lyfmail.com](https://lyfmail.com)
- **📓 Psychelog App:** [psychelog.lyfmail.com](https://psychelog.lyfmail.com)
- **🛠️ All Privacy-First Apps:** [lyfmail.com/privacy-first-apps](https://lyfmail.com/privacy-first-apps)
- **📱 PWA:** [app.lyfmail.com](https://app.lyfmail.com)
- **📚 Documentation:** [docs.lyfmail.com](https://docs.lyfmail.com)
- **🎨 Brand Assets:** [github.com/lyfmail-official/lyfmail-brand-assets](https://github.com/lyfmail-official/lyfmail-brand-assets)
- **🐦 X / Twitter:** [LYF Mail](https://x.com/lyfmailcom)
- **📘 Facebook:** [LYF Mail](https://www.facebook.com/thelyfmail)
- **▶️ YouTube:** [LYF Mail](https://m.youtube.com/channel/UCurymhWrl2nkvv31uJMuc0g)
- **💼 LinkedIn:** [LYF Mail](https://www.linkedin.com/company/lyf-mail)
- **📧 General Email:** contact@lyfmail.com
- **🆘 Support:** [support.lyfmail.com](https://support.lyfmail.com)

---

*"Every Choice Shapes Tomorrow"*

**Maintained by [LYF Mail](https://lyfmail.com)** · Founded by [Ajay Kumar Chaudhary](https://github.com/lyfmail) · Varanasi, Uttar Pradesh, India · Since 2020

---

## 💬 Frequently Asked Questions

**Q: Is Psychelog medical care or a replacement for therapy?**  
A: No. Psychelog is a journal and reflection tool, not medical care. It does not diagnose or treat any condition. Please work with a qualified professional where you need support.

**Q: What happens if I forget my password?**  
A: There is no recovery, by design: nobody can read your journal, including us. You can restore a backup whose password you remember, or erase the device and start fresh.

**Q: Does Psychelog send my writing anywhere?**  
A: No, unless you turn on optional sync. Even then the server stores only one opaque encrypted file that it cannot read or search.

**Q: How are my entries encrypted?**  
A: With AES-256-GCM in your browser. The key is derived from your password using PBKDF2-HMAC-SHA256 with 310,000 iterations and a random salt, and it lives only in memory while the vault is unlocked.

**Q: Can I share my journal with a therapist?**  
A: Yes. Export a date range as a CSV spreadsheet or a PDF summary. Voice memos are never included.

**Q: Does it work offline and in Hindi?**  
A: Yes. It is an offline-first PWA, and the whole interface switches between English and हिन्दी.

**Q: Is Psychelog free to use?**  
A: Yes. Psychelog is free to use under the MIT License, a project by [LYF Mail](https://lyfmail.com).

**Q: Can I contribute to Psychelog?**  
A: Yes. We welcome developers, designers, writers, translators and accessibility advocates. Please read [`CONTRIBUTING.md`](CONTRIBUTING.md) and [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) first.

**Q: How do I report a bug or a security issue?**  
A: Open a [GitHub issue](https://github.com/lyfmail-official/psychelog/issues) for bugs. For security vulnerabilities, **do not** open a public issue — follow [`SECURITY.md`](SECURITY.md).

---

*This README is maintained by the LYF Mail team. For issues, feature requests or contributions, please visit our [GitHub repository](https://github.com/lyfmail-official/psychelog).*
