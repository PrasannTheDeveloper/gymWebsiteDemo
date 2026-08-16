# IRON FORGE FITNESS // High-Performance Athletic Compound

A modern, high-performance website for **Iron Forge Fitness**, an industrial athletic and strength compound. Built with [Astro](https://astro.build) for blazing speed, zero runtime overhead, and responsive aesthetics.

---

## ⚡ Features

- **Hero Section**: Dynamic high-impact headline, social proof badge, CTA buttons, and interactive facility status ticker.
- **Philosophy & Blueprint**: Core principles, training pillars, and athletic values.
- **Programs Matrix**: Detailed breakdown of Barbell & Powerlifting, Functional Engine / Hyrox, Combat Conditioning, and Cryo Recovery.
- **Interactive Facility Tour**: Tabbed visual showcase with equipment and amenities.
- **Elite Coaches**: Trainer bios, certifications, and specialties.
- **Weekly Schedule**: Class schedules filterable by training discipline.
- **Member Transformations**: Real progress stories, metrics, and testimonials.
- **1-Rep Max & Calorie Calculator**: Interactive browser-based fitness tools.
- **Transparent Tiered Memberships**: Day pass, Standard Iron, and Black Card All-Access with feature checklists.
- **Location & Compound Map**: Hours, address, parking info, and direct contact.
- **Interactive Free Trial Modal & Toast Notifications**: Frictionless lead capture.

---

## 🛠️ Tech Stack

- **Framework**: [Astro](https://astro.build)
- **Styling**: Modern Vanilla CSS with customized design tokens and smooth micro-animations
- **Hosting**: [Cloudflare Pages](https://pages.cloudflare.com)
- **CI/CD**: GitHub + Cloudflare Pages automated deployments

---

## 🚀 Getting Started

### Prerequisites

- Node.js >= 22.12.0
- npm / pnpm / yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/PrasannTheDeveloper/gymWebsiteDemo.git
cd gymWebsiteDemo

# Install dependencies
npm install

# Start development server
npm run dev
```

### Production Build

```bash
npm run build
npm run preview
```

---

## ☁️ Deployment

Deployed to Cloudflare Pages:

```bash
# Deploy using Wrangler
npm run build
npx wrangler pages deploy dist --project-name=gym-website-demo
```
