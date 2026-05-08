# Freelancer Portfolio Website

**Production-Ready | Git Flow Workflow | Team Collaboration**

A professional, responsive freelancer portfolio website built with semantic HTML5 and modern CSS3. Implements Git Flow branching strategy with complete team collaboration and code review practices.

## 🎯 Project Status

✅ **PRODUCTION DEPLOYED** — Main branch ready for live hosting  
✅ **All 5 Pages Complete** — Home, Services, Contact, Portfolio, Blog  
✅ **Responsive Design** — Mobile-first CSS with media queries  
✅ **Semantic Markup** — HTML5 accessibility standards  
✅ **Team Review Complete** — All PRs reviewed and merged  

---

## 📁 Project Structure

```
freelancer-portfolio-website/
├── public/
│   ├── index.html              # Home page (hero + navigation hub)
│   ├── services.html           # Services showcase & CTA
│   ├── contact.html            # Contact form + business details
│   ├── portfolio.html          # Project showcase grid
│   ├── blog.html               # Article listing
│   └── assets/
│       └── css/
│           └── style.css       # Unified responsive stylesheet
├── README.md                   # Project documentation
└── .gitignore                  # Git ignore rules
```

---

## 🌐 Pages Overview

### 1. **Home Page** (`index.html`)
- Hero section with brand intro
- Navigation hub to all 5 pages
- Featured work teaser
- Dynamic footer with current year
- Semantic header/nav/main/footer structure

### 2. **Services Page** (`services.html`)
- Service listing (Web Development, UI/UX Design, Maintenance)
- Call-to-action button
- Responsive card layout
- Links to contact page for inquiries

### 3. **Contact Page** (`contact.html`)
- Accessible contact form (name, email, message)
- Business contact details (email link, location, availability)
- Responsive 2-column layout (form + sidebar)
- Form validation with HTML5 input types

### 4. **Portfolio Page** (`portfolio.html`)
- Project showcase with responsive grid
- Project cards with title, description, and links
- 3+ placeholder projects
- Semantic article structure
- Mobile-friendly card layout

### 5. **Blog Page** (`blog.html`)
- Article listing with semantic markup
- Post metadata (title, summary, date, author)
- Accessibility skip links
- Screen reader optimized

### 6. **Unified Stylesheet** (`assets/css/style.css`)
- CSS Variables: `--bg`, `--text`, `--muted`, `--accent`, `--max-width`, `--gap`, `--radius`
- Global: typography, box-sizing, responsive
- Components: header, nav, hero, forms, buttons, grid layouts
- Responsive breakpoints: 800px, 600px
- No inline styles — all centralized

---

## 🚀 Quick Start

### Local Development

1. **Clone the repository:**
   ```bash
   git clone https://github.com/shaafeadawood/freelancer-portfolio-website.git
   cd freelancer-portfolio-website
   ```

2. **Configure Git (repository-level):**
   ```bash
   git config user.name "Your Name"
   git config user.email "your.email@example.com"
   ```

3. **Switch to develop branch:**
   ```bash
   git checkout develop
   ```

4. **Open in browser:** Simply open any `.html` file in `public/` folder

---

## 🔄 Git Flow Workflow

This repository follows **Git Flow** branching strategy:

```
main (production)
  ↑
  └─ release/v1.0 (release prep)
       ↑
       └─ develop (integration branch)
            ↑
            ├─ feature/home-page ✓ (merged)
            ├─ feature/services-page ✓ (merged)
            ├─ feature/contact-page ✓ (merged)
            ├─ feature/portfolio-page ✓ (merged)
            └─ feature/blog-page ✓ (merged)
```

### Development Workflow

1. **Create feature branch from develop:**
   ```bash
   git checkout develop
   git pull origin develop
   git checkout -b feature/your-feature-name
   ```

2. **Make changes, commit, and push:**
   ```bash
   git add .
   git commit -m "feat: descriptive message"
   git push -u origin feature/your-feature-name
   ```

3. **Open Pull Request:**
   - PR target: `develop` branch
   - Add reviewers for code review
   - Merge after approval (squash commit)

4. **Release to Production:**
   ```bash
   git checkout develop
   git pull origin develop
   git checkout -b release/v1.0
   git push -u origin release/v1.0
   # Create PR from release/v1.0 → main
   ```

### Branch Protection Rules

- ✅ Require pull request before merge
- ✅ Require approvals from reviewers
- ✅ No direct pushes to `develop` or `main`
- ✅ No force pushes allowed

---

## 👥 Team Members

| Name | Role | GitHub |
|------|------|--------|
| Shaafea Dawood | Lead Developer | [@shaafeadawood](https://github.com/shaafeadawood) |
| Muhammad Mujtaba Haider | Developer | [@muhammad-mujtaba-haider-naqvi](https://github.com/muhammad-mujtaba-haider-naqvi) |
| Instructor | Reviewer | zsaing |

---

## 📋 Merge History

| PR | Feature | Status | Commit |
|----|---------|--------|--------|
| #8 | Home page | ✅ Merged | 37f833d |
| #9 | Services page | ✅ Merged | fd640f1 |
| #10 | Contact page | ✅ Merged | e1f0576 |
| #6 | Blog page | ✅ Merged | 268fab8 |
| #7 | Portfolio page | ✅ Merged | 2df55e4 |
| #11 | Release v1.0 | ✅ Merged to main | b012398 |

---

## 🎨 CSS Features

- **Responsive Design:** Mobile-first approach with media queries
- **CSS Variables:** Easy theme customization
- **Semantic HTML:** Proper heading hierarchy and ARIA labels
- **Accessibility:** Form labels, skip links, color contrast
- **Performance:** Minimal CSS, no frameworks, fast load times

### CSS Breakpoints

- **Desktop:** 1200px+
- **Tablet:** 800px - 1199px
- **Mobile:** < 600px

---

## ✨ Technologies

- **HTML5** — Semantic markup only
- **CSS3** — Responsive design with media queries
- **Git Flow** — Professional version control
- **GitHub** — Repository & collaboration

**No frameworks, no dependencies** — Pure web standards.

---

## 🚢 Deployment

### Production Status: ✅ LIVE

The `main` branch contains the production-ready code:

```bash
# Latest production commit
git show HEAD
# Output: Release v1.0: Freelancer Portfolio Website
```

All files committed to main:
- ✅ 5 HTML pages
- ✅ Unified CSS stylesheet
- ✅ .gitignore
- ✅ README.md

**Hosting ready:** Upload `public/` folder to your hosting provider.

---

## 📝 Contributing

1. Always work on feature branches
2. Create PRs against `develop`
3. Request code reviews before merge
4. Use squash commits for clean history
5. Write clear commit messages

---

## 📧 Contact

For questions about the project:
- **Lead:** Shaafea Dawood (@shaafeadawood)
- **Email:** fa23-bcs-155@cuilahore.edu.pk

---

**Last Updated:** May 8, 2026  
**Version:** v1.0 (Production Release)  
**License:** Open Source
