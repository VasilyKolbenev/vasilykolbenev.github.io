# Global Discoverability Checklist for vasilykolbenev.com

## ✅ Already Done (in index.html)

### Technical SEO
- **Title tag** — keyword-rich, under 60 chars: "Vasily Kolbenev — AI Solutions Architect | LLM, RAG, Computer Vision Systems"
- **Meta description** — compelling, under 155 chars, with key terms
- **Canonical URL** — `<link rel="canonical">`
- **Semantic HTML** — proper `<header>`, `<main>`, `<section>`, `<article>`, `<footer>`, `<nav>` tags
- **Heading hierarchy** — single `<h1>`, meaningful `<h2>`s and `<h3>`s per section
- **ARIA labels** — sections, navigation, lists annotated for accessibility
- **Alt text** on images with name + role
- **Skip-to-content** link for accessibility
- **`hreflang`** tags for international reach
- **Noscript fallback** so content loads without JS

### Structured Data (JSON-LD)
- **Person** schema — name, job title, skills, offers, sameAs links
- **WebSite** schema
- **WebPage** schema with dates
- **ItemList** schema for portfolio projects
- **Service** offers schema — each service type listed

### Social / Sharing
- **Open Graph** tags (Facebook, LinkedIn, WhatsApp, Slack)
- **Twitter Card** meta tags
- **og:image** placeholder (you need to create the actual image — see below)

---

## 🔲 You Need To Do

### 1. Domain & Hosting
- [ ] Buy a domain (e.g., `vasilykolbenev.com` or `vasily.ai`)
- [ ] Host on **Vercel**, **Cloudflare Pages**, or **Netlify** (all free, fast CDN, global edge)
- [ ] Enable **HTTPS** (automatic on all three platforms)
- [ ] Set up **www → non-www** redirect (or vice versa)

### 2. Create OG Image
- [ ] Create a 1200×630px image for social sharing previews
- [ ] Include: your name, "AI Solutions Architect", a dark theme matching the site
- [ ] Place at `/og-image.jpg` on your domain
- [ ] Tools: Figma, Canva, or https://og-image.vercel.app

### 3. Add Real Photo
- [ ] Replace the base64 placeholder with a proper optimized photo
- [ ] Use WebP format, 384×680px or similar
- [ ] Add to your hosting, reference via relative URL

### 4. Google Search Console
- [ ] Go to https://search.google.com/search-console
- [ ] Add your domain, verify ownership (DNS TXT record is easiest)
- [ ] Submit your sitemap: `https://vasilykolbenev.com/sitemap.xml`
- [ ] Request indexing for your main page

### 5. Bing Webmaster Tools
- [ ] Go to https://www.bing.com/webmasters
- [ ] Import from Google Search Console (one click)
- [ ] This also covers Yahoo and DuckDuckGo to some extent

### 6. Google Business Profile (optional but powerful)
- [ ] If you have a physical location or work from a city, create a Google Business Profile
- [ ] Category: "IT Consultant" or "Software Company"
- [ ] Link to your website

### 7. Backlinks & Presence
These are the **#1 factor** for global ranking:
- [ ] **GitHub** — ensure your profile links to your site (already have repos, good)
- [ ] **LinkedIn** — create/update profile, link to site, post about your projects
- [ ] **Dev.to / Medium / Habr** — write 2-3 articles about your AI projects, link back
- [ ] **Product Hunt** — launch SerpentRAG or LLM Forge there
- [ ] **Hacker News** — share interesting technical posts
- [ ] **Reddit** — share in r/MachineLearning, r/LocalLLaMA, r/LangChain
- [ ] **Stack Overflow** — answer AI/LLM questions, link profile to site
- [ ] **Hugging Face** — create a profile, link to your projects

### 8. Content Strategy (for ongoing SEO)
Consider adding a `/blog` section with posts like:
- "How I Built a Production RAG System with Qdrant and Neo4j"
- "Architecture Patterns for Multi-Agent Voice Assistants"
- "Self-Hosted LLM Serving: vLLM vs Ollama in Production"
- "Computer Vision Pipeline for Geological Core Analysis"

Each post = new indexed page = more search surface. Write 1-2 per month.

### 9. Performance
- [ ] Run Google PageSpeed Insights after deployment
- [ ] Target 90+ on mobile and desktop
- [ ] The current HTML file is already lightweight (~25KB), should score well
- [ ] Add `loading="lazy"` to any below-fold images you add later

### 10. Analytics
- [ ] Add **Google Analytics 4** or **Plausible** (privacy-friendly) to track visitors
- [ ] Set up goals: contact clicks, GitHub clicks, project views

---

## Search Queries You Should Rank For

Primary targets:
- "AI solutions architect"
- "freelance AI architect"
- "LLM consultant"
- "RAG platform architect"
- "hire AI engineer"
- "production AI systems consultant"

Long-tail targets:
- "AI architect for agentic workflows"
- "computer vision consultant oil and gas"
- "self-hosted LLM infrastructure expert"
- "LangGraph production deployment"
- "hire RAG system architect"

---

## File Checklist

```
your-site/
├── index.html          ← Main page (provided)
├── sitemap.xml         ← For search engines (provided)
├── robots.txt          ← Crawler rules (provided)
├── og-image.jpg        ← You create (1200×630)
├── favicon.ico         ← You create (32×32)
└── blog/               ← Future articles
```
