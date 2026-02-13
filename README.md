# MouldBlitz Website — Astro + Tailwind Edition

A modern, blazing-fast rebuild of the MouldBlitz website using **Astro** and **Tailwind CSS**.

## 🚀 Tech Stack

- **Astro** — Static site generator for lightning-fast performance
- **Tailwind CSS** — Utility-first CSS framework
- **TypeScript** — Type-safe JavaScript
- **Modern Images** — Unsplash integration for compelling visuals

## 📦 Installation

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## 🎨 What's New

### Design Improvements
- **Modern Hero Section** — Full-screen background with gradient overlay
- **Floating Coupon Cards** — Rotated, attention-grabbing offer cards
- **Image-First Services** — Each service card has a compelling background image
- **Dark Mode Contrast** — "Why Different" section uses dark theme for impact
- **Animated Gallery** — Hover effects on real job photos
- **Responsive Timeline** — Process steps with visual timeline

### Performance
- ⚡ Astro's partial hydration — zero JavaScript by default
- 🖼️ Optimized images via CDN
- 📱 Mobile-first responsive design
- 🔍 SEO-ready meta tags

## 📝 Customization

### Update Contact Details
Edit the phone number in these files:
- `src/components/Header.astro`
- `src/components/Hero.astro`
- `src/components/Contact.astro`

### Replace Images
Replace Unsplash URLs with your own photos in:
- `src/components/Hero.astro` — Hero background
- `src/components/Services.astro` — Service cards
- `src/components/Gallery.astro` — Gallery grid

### Update Colors
Edit `src/styles/global.css` to change the color scheme:
```css
--color-primary: #0066CC;
--color-accent: #00CC66;
--color-accent-orange: #FF6B35;
```

## 🌐 Deployment

### Netlify (Recommended)
```bash
npm run build
# Deploy the 'dist' folder
```

### Vercel
```bash
vercel --prod
```

### GitHub Pages
```bash
npm run build
# Commit and push 'dist' to gh-pages branch
```

## 📁 Project Structure

```
mouldblitz-astro/
├── src/
│   ├── components/      # Reusable Astro components
│   │   ├── Header.astro
│   │   ├── Hero.astro
│   │   ├── Services.astro
│   │   ├── WhyDifferent.astro
│   │   ├── Process.astro
│   │   ├── Pricing.astro
│   │   ├── Gallery.astro
│   │   ├── Reviews.astro
│   │   ├── Contact.astro
│   │   └── Footer.astro
│   ├── layouts/         # Page layouts
│   │   └── Layout.astro
│   ├── pages/           # Route pages
│   │   └── index.astro
│   └── styles/          # Global styles
│       └── global.css
├── astro.config.mjs
├── package.json
└── README.md
```

## 🎯 Features Preserved

All conversion-optimized elements from the original:
- ✅ Multiple CTAs (call, text, email, form)
- ✅ Trust signals (reviews, stats, certifications)
- ✅ Objection handling (Why Different section)
- ✅ Transparent pricing
- ✅ Urgency messaging
- ✅ Social proof (testimonials)
- ✅ Awaab's Law compliance focus

## 📱 Responsive Breakpoints

- Mobile: < 640px
- Tablet: 640px - 1024px  
- Desktop: > 1024px

## 🔧 Next Steps

1. **Add Real Images** — Replace Unsplash URLs with actual job photos
2. **Connect Form** — Wire up the contact form to EmailJS or your backend
3. **Add Analytics** — Google Analytics or Plausible
4. **SEO** — Add structured data (Schema.org) for local business
5. **Blog** — Add `/blog` route for content marketing

## 📄 License

Copyright © 2026 MouldBlitz. All rights reserved.