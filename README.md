# Alter Coding — Company Showcase Website

A professional dark-themed company website built with **Astro**, **HTML**, and **CSS**. Showcases services, pricing packages, projects, and team information for Alter Coding.

## 🚀 Quick Start

### Prerequisites
- [Node.js](https://nodejs.org/) 18+ installed
- npm (comes with Node.js)

### Installation

```bash
# Clone or download the project
cd AlterCoding2

# Install dependencies
npm install

# Start development server
npm run dev
```

The site will be available at `http://localhost:4321`.

### Build for Production

```bash
npm run build
```

The built site will be in the `.vercel/output/` directory (using the Vercel adapter).

### Preview Production Build

```bash
npm run preview
```

## 📁 Project Structure

```
AlterCoding2/
├── public/
│   └── logo.png              # Company logo
├── src/
│   ├── components/
│   │   ├── Header.astro       # Navigation header
│   │   └── Footer.astro       # Site footer
│   ├── layouts/
│   │   └── Layout.astro       # Base HTML layout
│   ├── pages/
│   │   ├── index.astro        # Home page
│   │   ├── services.astro     # Services page
│   │   ├── pricing.astro      # Pricing & packages
│   │   ├── projects.astro     # Projects & team
│   │   └── contact.astro      # Contact page
│   └── styles/
│       └── global.css         # Global styles
├── astro.config.mjs           # Astro configuration
├── package.json               # Dependencies
└── README.md                  # This file
```

## ✏️ Customization

All content is written directly inside each `.astro` page file. To edit:

### Contact Information
- **Email**: Search for `altercode.online@gmail.com` and replace
- **WhatsApp**: Search for `9342289593` and replace
- **Contact Person**: Search for `Magi Nandhu R` and replace

### Prices
- Edit `src/pages/pricing.astro` — prices are displayed directly in the HTML
- Also update the pricing preview in `src/pages/index.astro`

### Services
- Edit `src/pages/services.astro` — each service is a card in the HTML

### Projects
- Edit `src/pages/projects.astro` — each project is a card with description and tech tags

### Team Members
- Edit `src/pages/projects.astro` — team section at the bottom
- Replace sample `[Team Member Name]` entries with real team data

### Logo
- Replace `public/logo.png` with your updated logo

### Contact Form
- Form endpoint is configured live with Formspree: `https://formspree.io/f/mbgdwejp`
- Form submissions arrive directly at `altercode.online@gmail.com`
- Includes AJAX submission with inline success and error feedback banners

## 🚢 Deployment on Vercel

### Option 1: Vercel CLI
```bash
npm i -g vercel
vercel
```

### Option 2: Vercel Dashboard
1. Push your code to GitHub
2. Go to [vercel.com](https://vercel.com) and import the repository
3. Vercel auto-detects Astro and deploys

### Option 3: Manual
```bash
npm run build
# Upload the .vercel/output/ directory
```

## 🎨 Design Details

- **Theme**: Premium dark with black backgrounds, blue (#4f7df5) and violet (#8b5cf6) accents
- **Typography**: Inter font family
- **Responsive**: Mobile-first design (360px → 768px → 1440px)
- **Layout**: CSS Grid and Flexbox
- **Animations**: Subtle hover effects and fade-in animations

## 📄 Pages

| Page | URL | Description |
|------|-----|-------------|
| Home | `/` | Hero, company intro, featured services, projects, pricing |
| Services | `/services` | Freelance & academic services with detailed cards |
| Pricing | `/pricing` | Three packages with comparison table |
| Projects | `/projects` | Project showcase and team section |
| Contact | `/contact` | Contact form, WhatsApp, email, and info |

## 📝 License

© Alter Coding. All rights reserved.
