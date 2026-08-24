# Modern Business & Company Landing Page Template

A clean, responsive, and high-converting Landing Page built with pure **HTML5, CSS3, and vanilla JavaScript**. No dependencies or build steps required.

---

## 🚀 Quick Start

### 1. View in Browser
Simply double-click [`index.html`](index.html) or right-click and open it in Google Chrome, Microsoft Edge, Firefox, or Safari.

### 2. Project Directory Structure
```
business-landing-page/
│
├── index.html          # Main HTML document & section layouts
├── css/
│   └── style.css       # Design tokens, variables, typography & layout styles
├── js/
│   └── main.js         # Interactive features (Navbar, Stats counters, FAQ accordion, Form validation)
└── README.md           # Documentation & customization guide
```

---

## 🎨 Easy Customization

### Change Colors & Theming
Open [`css/style.css`](css/style.css) and adjust the `:root` CSS variables at the top of the file:
```css
:root {
  --primary-color: #2563eb;       /* Primary brand color */
  --primary-hover: #1d4ed8;       /* Primary button hover */
  --secondary-color: #0f172a;     /* Dark headings & footer background */
  --accent-gradient: linear-gradient(135deg, #2563eb 0%, #7c3aed 100%);
}
```

### Change Business Name & Text
Open [`index.html`](index.html) and update:
- Company Name: Search for `ApexDigital` and replace with your brand.
- Contact Details: Update email, phone number, and address in the `#contact` section and footer.
- Pricing Tiers: Modify prices and feature bullet points under the `#pricing` section.
- Services & Portfolio: Replace the service titles and project descriptions to showcase your exact offerings.

---

## 🌐 Free Hosting & Deployment Options

1. **GitHub Pages (Free)**:
   - Push this directory to a GitHub repository.
   - Go to **Settings > Pages**, choose the `main` branch, and click **Save**.
2. **Netlify (Free)**:
   - Drag and drop the `business-landing-page` folder into Netlify Drop ([app.netlify.com/drop](https://app.netlify.com/drop)).
3. **Vercel (Free)**:
   - Import your repository or deploy via the Vercel CLI.
