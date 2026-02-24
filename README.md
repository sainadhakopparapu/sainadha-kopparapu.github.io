# Sainadha Kopparapu — Portfolio

Personal portfolio site built with pure HTML, CSS, and JavaScript. Deployable on GitHub Pages.

---

## 🚀 Deploy to GitHub Pages

1. Create a repo named **`sainadha-kopparapu.github.io`** on GitHub
2. Upload the contents of this folder (just `index.html` and `README.md`)
3. Go to repo **Settings → Pages → Source → main branch**
4. Your site will be live at `https://sainadha-kopparapu.github.io`

---

## ✉️ Set Up Contact Form (Formspree) — 5 minutes

The contact form sends messages directly to your email using [Formspree](https://formspree.io) — free, no backend needed.

### Steps:

1. Go to **https://formspree.io** and sign up with your Gmail
2. Click **"+ New Form"**
3. Set **"Send submissions to"** → `sainadha.kopparapu@gmail.com`
4. Copy your **Form ID** (looks like: `xpwzgkrd`)
5. Open `index.html` and find this line:

```js
const res = await fetch('https://formspree.io/f/YOUR_FORM_ID', {
```

6. Replace `YOUR_FORM_ID` with your actual form ID:

```js
const res = await fetch('https://formspree.io/f/xpwzgkrd', {
```

7. Save and push to GitHub — done! Every message now goes to your email.

---

## ✏️ Customise

| What | Where in `index.html` |
|------|----------------------|
| GitHub links | Search `sainadha-kopparapu` and replace with your GitHub username |
| LinkedIn link | Replace `linkedin.com/in/sainadha-kopparapu` |
| Project GitHub links | Find each `.project-link` href |
| Experience / Projects | Update the timeline and project card sections |

---

## 🛠 Tech Stack

- Plain HTML + CSS + JavaScript — no build tools, no dependencies
- Google Fonts (Syne, DM Sans, DM Mono)
- Formspree for contact form
- Intersection Observer API for scroll animations
