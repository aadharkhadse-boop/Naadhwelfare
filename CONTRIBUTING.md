# Contributing to the NAADH Welfare Foundation website

Thank you for your interest in improving this project! Whether you're fixing a
typo, improving accessibility, or adding a feature, contributions of every size
are welcome.

## Ways to help

- 🐛 **Report a bug** — open an issue describing what you saw and what you expected.
- 💡 **Suggest an improvement** — open an issue to discuss it before large changes.
- 🌍 **Translations** — help make the site available in Marathi, Hindi, and other languages.
- ♿ **Accessibility** — improvements to contrast, keyboard navigation, and screen-reader support are especially valued.
- 📝 **Content & copy** — clearer, warmer, or more accurate wording.

## Making a change

1. **Fork** the repository and create a branch:
   ```bash
   git checkout -b my-improvement
   ```
2. Make your edits. The whole site is in [`index.html`](index.html) — no build step.
3. **Test locally** by opening the file or running `python3 -m http.server 8000`.
   Please check your change in **both light and dark themes** and on a **narrow
   (mobile) window**.
4. **Commit** with a clear message:
   ```bash
   git commit -m "Improve contrast on program cards in dark mode"
   ```
5. **Push** and open a **Pull Request** describing what changed and why.

## Style guidelines

- Keep the site **dependency-free** — no frameworks or build tooling.
- Reuse the existing **CSS variables** (`--accent`, `--ink`, …) instead of hard-coded colors.
- Preserve accessibility: semantic HTML, visible focus states, `alt`/`aria` labels, and `prefers-reduced-motion` support.
- Match the existing formatting and indentation.

## Code of Conduct

By participating, you agree to uphold our [Code of Conduct](CODE_OF_CONDUCT.md).

## Questions?

Open an issue, or reach the Foundation at **naadhwelfarefoundation@gmail.com**
*(please confirm this address)*.
