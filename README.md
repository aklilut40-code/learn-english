# 🌿 语Learn — English Tutoring Website

> Speak with confidence. Learn with ease.

语Learn is a warm, responsive English tutoring website designed to help students discover personalized lessons and get in touch with their tutor.

## ✨ Features

- **Three connected webpages** with simple navigation
- **Responsive design** for phones, tablets, and desktops
- **Home page** with tutor introduction and clear calls to action
- **Lessons page** featuring conversation, grammar, exam preparation, and business English
- **Contact page** with a direct WhatsApp booking button
- **Shared stylesheet** for consistent design across every page
- Soft, friendly visual style using custom colors, rounded cards, and Google Fonts

## 📁 Project structure

```text
learn-english/
├── Index.html      # Home and tutor introduction
├── Lessons.html    # Lesson categories and testimonial
├── Contact.html    # Contact details and WhatsApp call to action
├── styles.css      # Shared responsive styles
└── README.md       # Project documentation
```

## 🚀 Run locally

No build tools or dependencies are required.

1. Clone the repository:

   ```bash
   git clone https://github.com/aklilut40-code/learn-english.git
   ```

2. Open the project folder.
3. Open `Index.html` in your browser.
4. Use the navigation menu to explore the Lessons and Contact pages.

For the best local development experience, serve the folder with a simple local server:

```bash
python3 -m http.server 8000
```

Then visit [http://localhost:8000/Index.html](http://localhost:8000/Index.html).

## 🧭 Pages

| Page | Purpose |
| --- | --- |
| `Index.html` | Introduces the tutor and the learning experience |
| `Lessons.html` | Shows available tutoring options and student feedback |
| `Contact.html` | Helps visitors contact the tutor through WhatsApp |

## 🎨 Design system

The site uses:

- **Fraunces** for expressive headings and branding
- **Nunito** for friendly, readable body text
- Warm cream backgrounds and rose accents
- Sage green highlights for trust and calm
- Rounded cards and pill-shaped buttons
- Mobile-first responsive behavior

Fonts are loaded from [Google Fonts](https://fonts.google.com/).

## 📱 Contact setup

The WhatsApp button currently uses the number configured in `Contact.html`:

```text
https://wa.me/251900000000
```

Replace `251900000000` with the tutor's real WhatsApp number, including the country code and without spaces or the `+` symbol.

## 🛠️ Customization

You can easily personalize the website by editing:

- Tutor information in `Index.html`
- Lesson descriptions in `Lessons.html`
- Contact details and WhatsApp number in `Contact.html`
- Colors, spacing, layout, and typography in `styles.css`

## 🌐 Deployment

Because this is a static website, it can be deployed with:

- GitHub Pages
- Netlify
- Vercel
- Cloudflare Pages
- Any static web hosting service

## 📄 License

This project is available for personal and educational use. Add a license file if you plan to distribute or reuse it publicly.

---

Made with care for learners building real English confidence. 💬
