# CraftAI 🎨
### Empowering Artisans with AI

CraftAI is an AI-powered platform built for artisans and craftspeople to grow their business using the power of Gemini AI. From generating product stories to optimizing social media content, CraftAI gives traditional artisans modern digital tools.

---

## Features

- **AI Story Generator** — Create compelling narratives about your craft and heritage using Gemini AI
- **Image Analysis** — Upload photos of your artisan products and automatically generate marketing copy
- **Social Media Optimizer** — Get AI-suggested hashtags, captions, and posting strategies for Instagram, Facebook, and Twitter
- **Product Listing Optimizer** — Generate SEO-friendly titles and descriptions for online marketplaces
- **Heritage Storytelling** — Explain traditional techniques and historical significance of your craft
- **Market Trends** — View demand patterns and pricing suggestions for your craft category
- **AI Portfolio Builder** — Generate an artist statement and build a portfolio showcase with AI assistance

---

## Tech Stack

- **Frontend** — React, TypeScript, Vite, Tailwind CSS, shadcn/ui
- **Backend** — Node.js, Express, TypeScript
- **AI** — Google Gemini API
- **Database** — Drizzle ORM
- **Deployment** — Railway, Vercel

---

## Getting Started

### Prerequisites
- Node.js 18+
- A Google Gemini API key

### Installation

```bash
git clone https://github.com/yashikarora22/hackathon_gen_ai.git
cd hackathon_gen_ai
npm install
```

### Environment Setup

Create a `.env` file in the root and add your Gemini API key:

```
GEMINI_API_KEY=your_api_key_here
```

### Run Locally

**On Windows:**

First update the `dev` script in `package.json`:
```json
"dev": "cross-env NODE_ENV=development tsx server/index.ts"
```

Then run:
```bash
npm run dev
```

Open [http://localhost:5000](http://localhost:5000) in your browser.

---

## Live Demo

[https://hackathon-gen-ai-flax.vercel.app](https://hackathon-gen-ai-flax.vercel.app)

---

## Built at a Hackathon 🏆

This project was built as part of a Gen AI hackathon to help traditional artisans leverage AI tools for digital growth and marketing.
