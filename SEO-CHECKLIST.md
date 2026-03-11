# Global Discoverability Checklist for vasilykolbenev.github.io

## ✅ Done

### Technical SEO
- [x] **Title tag** — keyword-rich: "Vasily Kolbenev — AI Solutions Architect | LLM, RAG, Computer Vision Systems"
- [x] **Meta description** — compelling, under 155 chars, with key terms
- [x] **Canonical URL** — `<link rel="canonical">`
- [x] **Semantic HTML** — proper `<header>`, `<main>`, `<section>`, `<article>`, `<footer>`, `<nav>` tags
- [x] **Heading hierarchy** — single `<h1>`, meaningful `<h2>`s and `<h3>`s per section
- [x] **ARIA labels** — sections, navigation, lists annotated for accessibility
- [x] **Alt text** on images with name + role
- [x] **Skip-to-content** link for accessibility
- [x] **`hreflang`** tags for international reach
- [x] **Noscript fallback** so content loads without JS
- [x] **Favicon** — SVG emoji inline
- [x] **Theme-color** — for mobile browser chrome
- [x] **Mobile menu** — hamburger navigation for mobile devices

### Structured Data (JSON-LD)
- [x] **Person** schema — name, job title, skills, offers, sameAs links
- [x] **WebSite** schema
- [x] **WebPage** schema with dates
- [x] **ItemList** schema for portfolio projects
- [x] **Service** offers schema — each service type listed

### Social / Sharing
- [x] **Open Graph** tags (Facebook, LinkedIn, WhatsApp, Slack)
- [x] **Twitter Card** meta tags

### Hosting & Deployment
- [x] **GitHub Pages** — deployed at https://vasilykolbenev.github.io/
- [x] **HTTPS** — automatic via GitHub Pages
- [x] **Real photo** — added to hero portrait card

### Search Engine Registration
- [x] **Google Search Console** — verified, sitemap submitted, indexing requested
- [x] **Bing Webmaster Tools** — imported from Google, sitemap processing
- [x] **Yandex Webmaster** — verified, sitemap submitted

---

## 🔲 Next Steps

### 1. Buy Custom Domain
- [ ] Buy `vasilykolbenev.com` on **Namecheap** or **Porkbun** (~$9-10/year)
- [ ] In DNS settings, add 4 A-records pointing to GitHub Pages IPs:
  ```
  185.199.108.153
  185.199.109.153
  185.199.110.153
  185.199.111.153
  ```
- [ ] Add CNAME record: `www` → `vasilykolbenev.github.io`
- [ ] In GitHub repo Settings → Pages → Custom domain → enter `vasilykolbenev.com`
- [ ] Wait for SSL certificate (automatic, ~10 min)
- [ ] Update all URLs in `index.html`, `sitemap.xml`, `robots.txt` back to `vasilykolbenev.com`
- [ ] Re-submit sitemap in Google, Bing, Yandex with new domain
- [ ] Set up **www → non-www** redirect

### 2. Create OG Image (for social sharing previews)
- [ ] Create a **1200x630px** image with:
  - Your name: "Vasily Kolbenev"
  - Title: "AI Solutions Architect"
  - Dark theme matching the site (#09090b background)
  - Optional: subtle tech keywords or gradient
- [ ] Tools: **Figma**, **Canva**, or https://og-image.vercel.app
- [ ] Save as `og-image.jpg` in the site root
- [ ] Push to GitHub — social previews will start working immediately

### 3. Backlinks & Online Presence
These are the **#1 factor** for ranking:
- [ ] **GitHub profile** — add website link to bio
- [ ] **LinkedIn** — create/update profile, link to site, post about projects
- [ ] **Dev.to / Medium / Habr** — write 2-3 articles about AI projects, link back
- [ ] **Product Hunt** — launch SerpentRAG or LLM Forge
- [ ] **Hacker News** — share technical posts
- [ ] **Reddit** — share in r/MachineLearning, r/LocalLLaMA, r/LangChain
- [ ] **Hugging Face** — create profile, link to projects

### 4. Content Strategy (ongoing SEO growth)
Add a `/blog` section with posts like:
- "How I Built a Production RAG System with Qdrant and Neo4j"
- "Architecture Patterns for Multi-Agent Voice Assistants"
- "Self-Hosted LLM Serving: vLLM vs Ollama in Production"
- "Computer Vision Pipeline for Geological Core Analysis"

Each post = new indexed page = more search surface. Write 1-2 per month.

### 5. Analytics
- [ ] Add **Google Analytics 4** or **Plausible** (privacy-friendly)
- [ ] Set up goals: contact clicks, GitHub clicks, project views

### 6. Performance Check
- [ ] Run **Google PageSpeed Insights** — target 90+ on mobile and desktop
- [ ] Site is already lightweight (~25KB HTML), should score well

---

## Target Search Queries

**Primary:**
- "AI solutions architect"
- "freelance AI architect"
- "LLM consultant"
- "RAG platform architect"
- "hire AI engineer"
- "production AI systems consultant"

**Long-tail:**
- "AI architect for agentic workflows"
- "computer vision consultant oil and gas"
- "self-hosted LLM infrastructure expert"
- "LangGraph production deployment"
- "hire RAG system architect"

---

## Current File Structure

```
vasilykolbenev.github.io/
├── index.html                          ← Main page
├── photo.jpg                           ← Portrait photo
├── sitemap.xml                         ← For search engines
├── robots.txt                          ← Crawler rules
├── googlef080d3420ac52415.html         ← Google verification
├── yandex_25e869505e51bde0.html        ← Yandex verification
├── SEO-CHECKLIST.md                    ← This file
├── og-image.jpg                        ← TODO: create (1200x630)
└── blog/                               ← TODO: future articles
```
