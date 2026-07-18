
# Intern2Grow - Login Page

A responsive login page built with pure HTML and CSS, based on the Intern2Grow Figma design.

## 🔗 Live Preview
Open `index.html` in any modern web browser to view the page.

## 📁 Project Structure
├── index.html   # Markup, styles, and script all in one file
└── README.md    # Project documentation
## ✨ Features
- **Split-screen layout** — dark image panel ("Work with us") on the left, sign-in form on the right
- **Social login buttons** — "Continue with Google" and "Continue with Twitter" with inline SVG icons
- **Email & password fields** with a working **Show/Hide password toggle**
- **"Forget your password"** and **"Sign up"** links
- **Fully responsive** — panels sit side-by-side on desktop/tablet and stack vertically on mobile (under 640px)

## 🛠️ Built With
- HTML5
- CSS3 (Flexbox, media queries, CSS transitions)
- Vanilla JavaScript (for the password show/hide toggle)

## 📱 Responsive Breakpoints
| Breakpoint | Behavior |
|---|---|
| `> 900px` | Full two-column layout |
| `≤ 900px` | Reduced padding/font sizes, still side-by-side |
| `≤ 640px` | Panels stack vertically (image on top, form below) |
| `≤ 480px` | Smaller headings and tighter spacing for phones |

## 🎨 Customization
- **Background image:** Update the `background` property inside `.left-panel` with your own image URL.
- **Accent color:** The gold "Sign in" button color is set via `background: #b08d3f;` in `.signin-btn`.
- **Form logic:** The Sign in button has no backend connection yet — hook it up to your auth API.

## 🚀 Getting Started
```bash
git clone <your-repo-url>
cd intern2grow-login-page
# Just open index.html in your browser — no build step required
```

# Ahmed Saber - Portfolio2Grow

A responsive personal portfolio landing page built with pure HTML and CSS, based on the Intern2Grow Figma design.

## 🔗 Live Preview
Open `portfolio.html` in any modern web browser to view the page.

## ✨ Features
- **Navbar** with nav links, centered logo ("Portfolio2Grow"), and social icons (Instagram, Facebook, Twitter, LinkedIn)
- **Hero heading** with the profile name
- **Three-column layout** — Services list, circular profile photo, and bio/stats section
- **Stats section** — years of experience and client count
- **"Hire me" CTA button**
- **Fully responsive** — columns stack into a single centered layout on smaller screens, with the photo moving to the top

## 🛠️ Built With
- HTML5
- CSS3 (Flexbox, media queries, `aspect-ratio`)

## 📱 Responsive Breakpoints
| Breakpoint | Behavior |
|---|---|
| `> 900px` | Full three-column layout |
| `≤ 900px` | Columns stack vertically, centered, photo moves to top |
| `≤ 480px` | Smaller headings and tighter nav spacing for phones |

## 🎨 Customization
- **Profile photo:** Replace the `img src` inside `.photo-circle` with your own image.
- **Services:** Edit the three `.service-item` blocks (icon, title, description) to update your offerings.
- **Stats:** Update the numbers/labels inside `.stats` to reflect your real experience/clients.
- **Social links:** Update the `href` attributes in `.socials` to point to your real profiles.

## 🚀 Getting Started
```bash
git clone <your-repo-url>
cd portfolio2grow
# Just open portfolio.html in your browser — no build step required
```


