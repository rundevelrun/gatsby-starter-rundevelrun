---
emoji: "🚀"
title: "Customizing the Starter"
date: 2025-01-18 13:55:00
update: 2025-01-18 13:55:00
tags:
   - rundevelrun
   - customizing
series: "Getting Started with Gatsby Blog"
---

This template is designed for easy and flexible customization.

## 🧠 SEO Settings

Edit `src/components/SEO/index.jsx` to update meta tags, Open Graph settings, etc.

## 💻 Layout Components

- Header: `src/components/layout/Header/index.jsx`
- Footer: `src/components/layout/Footer/index.jsx`

Customize navigation, logo, dark mode toggle, and more here.

## ☺️ Customization
Edit the contents of `blog-config.js`

```javascript
module.exports = {
   title: "YOUR:BLOG:NAME",    // SEO Blog title
   headerTitle: "YOUR:<em style='color:#ed6c02'>BLOG</em>:NAME", // Logo 1
   headerSubTitle: "<em style='color:#ed6c02'>YOUR</em>:BLOG:<em style='color:#ed6c02'>NAME</em>", // Logo 2
   copyright: "©YOUR:BLOG:NAME", // copyright in footer
   author: "YOUR:NAME",  // Your Name
   siteUrl: "https://6developer.com/", // Your Site URL
   description: "Hi, Nice to meet you !",  // Blog description
   links: {
      github: "https://github.com/rundevelrun",
      ...
   },
   giscus: {
      ...
   },
   adsense: {
      ...
   }
}
```
