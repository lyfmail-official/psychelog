# Contributing to Psychelog

Thank you for your interest in improving **Psychelog**, part of the [LYF Mail](https://lyfmail.com) family of free, open-source, privacy-first tools.

By taking part, you agree to follow our [Code of Conduct](CODE_OF_CONDUCT.md).

## Core Principles

Every contribution should respect these principles:

- **Privacy-first** — do not add tracking, analytics, advertising, fingerprinting, or unnecessary data collection.
- **Minimal dependencies** — prefer built-in web platform features over frameworks and third-party libraries. Justify any new dependency in your pull request.
- **Performance-focused** — keep Psychelog fast on low-end devices, slow networks, and limited battery.
- **Accessibility-first** — every feature must work with a keyboard and a screen reader, and respect reduced-motion and contrast preferences.
- **Mental health respectful** — no gamification, no metrics pressure, no social comparison.

## Ways to Contribute

- Report bugs or suggest features through [GitHub Issues](https://github.com/lyfmail-official/psychelog/issues).
- Improve documentation, examples, and translations.
- Fix bugs or implement features from open issues.
- Review pull requests and test on different devices and browsers.

## Getting Started

1. **Fork** the repository and clone your fork:
   ```bash
   git clone https://github.com/<your-username>/psychelog.git
   cd psychelog
   ```
2. **Create a branch** with a descriptive name:
   ```bash
   git checkout -b fix/short-description
   ```
3. **Run locally** with any static file server:
   ```bash
   python -m http.server 8080
   # or
   npx serve .
   ```
4. **Make your changes**, keeping each pull request focused on one topic.
5. **Test** on at least one desktop and one mobile browser.
6. **Commit** with a clear message, for example `fix: correct label on settings toggle`.
7. **Push** and open a pull request against `main`.

## Pull Request Checklist

- [ ] The change is focused and clearly described.
- [ ] No tracking, analytics, or unnecessary data collection was added.
- [ ] No unnecessary dependencies were added.
- [ ] Keyboard navigation and screen-reader labels were checked for UI changes.
- [ ] Documentation was updated where needed.

## Reporting Security Issues

Please do **not** open a public issue for vulnerabilities. Follow [`SECURITY.md`](SECURITY.md).

## License

By contributing, you agree that your contributions will be licensed under the [MIT License](LICENSE).

## Questions?

Email contact@lyfmail.com or visit [support.lyfmail.com](https://support.lyfmail.com).
