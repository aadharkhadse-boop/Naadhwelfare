# NAADH Welfare Foundation — Website

The official website of **NAADH Welfare Foundation**, a registered non-profit
company in Nagpur, Maharashtra dedicated to **educational support services** —
tutoring, scholarships, digital literacy, and mentorship for underserved
children.

The name comes from **नाद (naad)** — *resonance* — the belief that a single
opportunity to learn can echo through a child's life and community.

> This is an **open-source** project. You are welcome to use it as a starting
> point for your own non-profit's website under the terms of the [MIT License](LICENSE).

---

## ✨ Features

- Single-page site: Home · About · Programs · Get Involved · Contact
- Fully responsive (mobile → desktop)
- **Light & dark themes** with a manual toggle (respects the visitor's OS setting)
- Animated "resonance" ripple motif on the hero canvas
- Accessible contact form that opens the visitor's email client (no backend required)
- Zero build step, zero dependencies — just one HTML file

## 🛠 Tech stack

Plain **HTML, CSS, and JavaScript** — no frameworks, no npm, no build tooling.
Everything (styles + scripts) is inlined in [`index.html`](index.html) so the
site is a single, portable, self-contained file.

## 🚀 Run it locally

No installation needed. Either:

```bash
# Option 1 — just open the file
open index.html          # macOS
xdg-open index.html      # Linux
start index.html         # Windows

# Option 2 — serve it (recommended, avoids browser file:// quirks)
python3 -m http.server 8000
# then visit http://localhost:8000
```

## 📁 Project structure

```
naadh-welfare-foundation/
├── index.html          # The entire website (HTML + CSS + JS inlined)
├── README.md           # This file
├── LICENSE             # MIT License
├── CONTRIBUTING.md     # How to contribute
├── CODE_OF_CONDUCT.md  # Community expectations
└── .gitignore
```

## 🎨 Customising the site

Everything lives in `index.html`. The most common edits:

| What to change        | Where to look |
|-----------------------|---------------|
| Colors / theme        | The `:root` CSS variables near the top of the `<style>` block (`--accent`, `--secondary`, `--ink`, …) |
| Fonts                 | The `--serif` and `--sans` variables |
| Email address         | Search for `naadhwelfarefoundation@gmail.com` (appears in the contact link and the form's `mailto:`) |
| Phone number          | Search for `add your number` in the Contact section |
| Programs / text       | The `<section id="programs">` and other section markup |
| Registration details  | The `.official` block in the Contact section and the footer |
| Social links          | Add them to the `<nav class="fnav">` in the footer |

## 🌐 Deploying

Because it's a static site, you can host it for **free** almost anywhere:

- **GitHub Pages** — push to [this repo](https://github.com/aadharkhadse-boop/Naadhwelfare),
  then enable Pages on the `main` branch. Your site will be live at
  `https://aadharkhadse-boop.github.io/Naadhwelfare`.
- **Netlify** — drag the folder onto [app.netlify.com/drop](https://app.netlify.com/drop).
- **Vercel** — `vercel` in this directory, or import the repo.
- **Cloudflare Pages** — connect the repo, no build command needed.

Clone it with:

```bash
git clone https://github.com/aadharkhadse-boop/Naadhwelfare.git
```

## 🤝 Contributing

Contributions are welcome — see [CONTRIBUTING.md](CONTRIBUTING.md). Please also
read our [Code of Conduct](CODE_OF_CONDUCT.md).

## 📄 License

Code is released under the [MIT License](LICENSE).
The **NAADH Welfare Foundation** name, logo, and organisational content remain
the property of the Foundation.

## 🏛 About the Foundation

- **CIN:** U85500ME2026NPL475367
- **Registered office:** 4/137 Raghuji Nagar, Manewada Road, Nagpur, Maharashtra 440024, India
- **Incorporated:** 20 June 2026 · RoC-Nagpur · Status: Active
