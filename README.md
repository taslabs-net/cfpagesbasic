# Professional Landing Page Template

A beautiful, professional landing page template for Cloudflare Pages. Drop-dead easy setup - just edit one config file and you're done!

## 🚀 Deploy to Cloudflare Pages

[![Deploy to Cloudflare Pages](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/taslabs-net/cfpagesbasic)

### Deployment Settings
When deploying, use these settings in Cloudflare Pages:
- **Build command:** `npm run build` (or leave empty)
- **Build output directory:** `/` (root directory)
- **Root directory:** `/`

## ✨ Features

- **🎨 Beautiful professional design** with gradient backgrounds and animations
- **⚡ One-click deployment** to Cloudflare Pages
- **📝 Super easy editing** - just edit one config file
- **📱 Fully responsive** - looks great on all devices
- **🔗 Social links** with hover effects
- **💼 Contact section** with email, phone, location
- **🎭 Auto-generated avatar** from your initials
- **🚀 Zero build process** - deploys instantly

## 📝 How to Customize Your Site

After deploying, it's incredibly simple:

1. Go to your forked repository on GitHub
2. Edit the `config.txt` file
3. Fill in your information (see example below)
4. Commit the changes
5. Done! Your professional landing page is live!

### Example config.txt:
```
FirstName=Tim
LastName=Smith
Email=tim@example.com
Phone=+1 (555) 123-4567
Title=Founder & CEO
Company=TAS Labs
Location=San Francisco, CA

LinkedIn=https://linkedin.com/in/timsmith
Twitter=https://twitter.com/timsmith
GitHub=https://github.com/timsmith
Website=https://timsmith.com

Headline=Building the Future of Technology
Tagline=Passionate entrepreneur and technology leader
AboutText=I'm a dedicated founder with over 10 years of experience in tech startups. I love building products that solve real problems and make people's lives better.
```

## 🛠️ Local Development

No build process needed! Just serve the files:

```bash
# Serve locally (any static server works)
python -m http.server 8000
# or
npx serve .
```

## 📁 Project Structure

```
cfpagesbasic/
├── config.txt           # Your personal info (edit this!)
├── index.html           # Beautiful landing page template
├── package.json         # Minimal package config for deployment
├── _headers             # Security headers for Cloudflare Pages
└── _redirects           # Routing configuration
```

## 🎨 What You Get

- **Hero section** with your name, title, company, and photo avatar
- **Social links** (LinkedIn, Twitter, GitHub, Website)
- **About section** with your custom description
- **Contact section** with email, phone, and location
- **Professional styling** with gradients and animations
- **Mobile-first responsive design**

## 📋 Requirements

- GitHub account (for editing config)
- Cloudflare account (for hosting)
- That's it! No coding knowledge needed.

---

*Built with ❤️ for simple, editable static sites*