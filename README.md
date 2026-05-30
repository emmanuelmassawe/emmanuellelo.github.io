# 🗂️ Emmanuel John Lelo — Portfolio Website

A modern, responsive personal portfolio website for **Emmanuel John Lelo**, Full-Stack Data Scientist & MLOps Engineer. Built with pure HTML, CSS, and JavaScript — no frameworks needed.

---

## 🌟 Live Preview

> Open `portfolio.html` directly in your browser — no server needed!

---

## ✨ Features

- 🗂️ **Three Pages** — Portfolio, Resume, and CV in one file
- 📬 **Contact Form** — Connected to FastAPI backend for real email delivery
- 🎨 **Modern Dark Design** — Teal gradient theme with smooth animations
- 📱 **Fully Responsive** — Works on mobile, tablet, and desktop
- 🖨️ **Print / Save PDF** — Resume and CV can be saved as PDF
- ⚡ **Animated Progress Bars** — Skill proficiency bars with scroll animation
- 🌀 **Fade-up Animations** — Smooth scroll reveal effects
- 🔗 **Smooth Navigation** — Active nav link tracking on scroll

---

## 📁 Project Structure

```
frontend/
├── portfolio.html     # Main file — entire website in one file
└── README.md          # This file
```

> 💡 The entire website lives in a **single HTML file** — easy to host anywhere!

---

## 📄 Pages Inside the Website

### 🗂️ Page 1 — Portfolio
Full interactive portfolio with:
- Hero section with animated background grid
- About section with stats
- Technical Skills cards
- Skill Proficiency bars
- Work Experience timeline
- Featured Projects grid
- Certifications & Education
- Contact form + social links

### 📄 Page 2 — Resume
Clean one-page resume with:
- Professional header with contact details
- Sidebar with skills, education, certifications
- Work experience with bullet points
- Key projects grid

### 📋 Page 3 — CV
Detailed Curriculum Vitae with:
- Full professional profile
- Detailed work experience cards
- Complete skills breakdown
- All 6 featured projects
- Education & certifications
- Key achievements with numbers
- Languages & soft skills
- Availability banner

---

## 🛠️ Tech Used

| Technology | Purpose |
|-----------|---------|
| HTML5 | Page structure |
| CSS3 | Styling & animations |
| JavaScript (Vanilla) | Interactivity & form submission |
| CSS Variables | Consistent theming |
| Intersection Observer API | Scroll animations |
| Fetch API | Sending form data to backend |

---

## ⚙️ Setup

### Option 1 — Open Directly (Simplest)

Just double-click `portfolio.html` — opens in your browser instantly. No installation needed!

### Option 2 — VS Code Live Server

1. Install **Live Server** extension in VS Code
2. Right-click `portfolio.html`
3. Click **"Open with Live Server"**

---

## 📬 Connecting the Contact Form to Backend

The contact form sends data to the FastAPI backend. Find this line in `portfolio.html`:

```javascript
const API_URL = 'http://localhost:8000';
```

| Environment | Value |
|------------|-------|
| Development (local) | `http://localhost:8000` |
| Production (live server) | `https://your-server.com` |

> ⚠️ Make sure the **backend server is running** before testing the contact form!

---

## 🎨 Color Theme

All colors use CSS variables — easy to customize:

```css
:root {
  --teal:    #0d9488;   /* Primary color */
  --teal2:   #14b8a6;   /* Lighter teal */
  --teal3:   #99f6e4;   /* Highlight */
  --dark:    #0f172a;   /* Background */
  --dark2:   #1e293b;   /* Card background */
  --accent:  #f59e0b;   /* Amber accent */
  --muted:   #94a3b8;   /* Muted text */
}
```

To change the theme — just update these variables at the top of the CSS!

---

## 🖨️ How to Save Resume / CV as PDF

1. Click **Resume** or **CV** tab in the navbar
2. Click **🖨️ Save PDF** button (top right)
3. In the print dialog — select **"Save as PDF"**
4. Click **Save**

---

## 📱 Responsive Breakpoints

| Screen | Layout |
|--------|--------|
| Desktop (> 760px) | Two-column layouts, full nav |
| Mobile (≤ 760px) | Single column, compact nav |

---

## 🚀 Sections You Can Customize

| Section | What to Update |
|---------|---------------|
| Hero | Name, title, description |
| About | Bio, location, email |
| Skills | Add/remove skill tags |
| Experience | Job roles, dates, descriptions |
| Projects | Project names, descriptions, tags |
| Certifications | Cert names, issuers, years |
| Contact | Email, LinkedIn, GitHub, Kaggle links |
| Resume & CV | Same info as above but formatted |

---

## 🌍 Hosting Options (Free)

| Platform | How |
|---------|-----|
| **GitHub Pages** | Push to GitHub → Enable Pages in settings |
| **Netlify** | Drag & drop `portfolio.html` |
| **Vercel** | Connect GitHub repo |

### GitHub Pages (Easiest)

```bash
git add portfolio.html README.md
git commit -m "initial portfolio"
git push
```

Then go to: **GitHub repo → Settings → Pages → Deploy from main branch**

Your site will be live at:
```
https://emmanuelmassawe.github.io/frontend/
```

---

## 🔗 Related Repository

This frontend works together with the backend API:

> 🔗 **Backend:** [github.com/emmanuelmassawe/backend](https://github.com/emmanuelmassawe/backend)

---

## 👤 Author

**Emmanuel John Lelo**
Full-Stack Data Scientist & MLOps Engineer
📧 leloemmanuel540@email.com
💼 [LinkedIn](https://linkedin.com/in/emmanuel-john-61b343334)
🐙 [GitHub](https://github.com/emmanuelmassawe)
🌍 Open to Remote — Europe & Worldwide

---

## 📄 License

MIT License — free to use and modify.
