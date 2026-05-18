# Edumynt Psychology

<!-- Replace with actual logo/banner image URL -->
<!-- ![Edumynt Psychology](https://psychology.edumynt.in/og-image.png) -->

**Explore the human mind and behavior.**

Edumynt Psychology is an open-source educational blog covering classical conditioning, cognitive psychology, learning theory, and more. Built with [Astro](https://astro.build).

🌐 **Live site:** [psychology.edumynt.in](https://psychology.edumynt.in)

---

## 📖 About

This blog publishes well-researched, accessible articles on psychology topics — from foundational theories to real-life applications. All content is free to read, share, and adapt under a copyleft license.

## 🤝 Contribute

We welcome contributions! You can help by:

### Writing Content
- Write new articles (EN or HI) on psychology topics
- Follow the content guidelines in [`CONTRIBUTING.md`](./CONTRIBUTING.md)
- Submit a pull request with your article in `src/content/posts/`

### Suggest Edits
- Found a typo, outdated info, or have a suggestion?
- Click the **"Suggest Edit"** button on any article page
- Or [open an issue](https://github.com/Edumynt/edumynt-psychology/issues/new?template=suggest-edit.md)

### Report Issues
- Broken links, rendering problems, or accessibility issues — [file a bug](https://github.com/Edumynt/edumynt-psychology/issues/new?template=bug-report.md)

## 🛠️ Tech Stack

- [Astro](https://astro.build) — Static site generator
- [MDX](https://mdxjs.com/) — Markdown + JSX for interactive content
- [Tailwind CSS](https://tailwindcss.com/) — Styling
- [GitHub Pages](https://pages.github.com/) — Hosting
- [Cloudflare](https://www.cloudflare.com/) — DNS + CDN

## 🚀 Local Development

```bash
# Clone the repo
git clone https://github.com/Edumynt/edumynt-psychology.git
cd edumynt-psychology

# Install dependencies
bun install

# Start dev server
bun run dev
# → http://localhost:4321

# Build for production
bun run build
# → Output in dist/
```

## 📁 Project Structure

```
edumynt-psychology/
├── src/
│   ├── content/
│   │   └── posts/          # Blog posts (MDX)
│   │       ├── en/         # English posts
│   │       └── hi/         # Hindi posts
│   ├── layouts/            # Page layouts
│   ├── components/         # Reusable components
│   ├── pages/              # Route pages
│   └── config.ts           # Site configuration
├── public/                 # Static assets
├── .github/
│   ├── workflows/          # CI/CD (deploy to GitHub Pages)
│   └── ISSUE_TEMPLATES/    # Issue templates
├── astro.config.mjs
└── package.json
```

## 📜 License

| Component | License |
|-----------|---------|
| **Code & Theme** | [GPL-3.0](LICENSE-GPL) |
| **Content & Articles** | [CC BY-SA 4.0](LICENSE-CC-BY-SA) |

In short: free to use, share, and adapt — as long as you give credit and share derivatives under the same license. See [LICENSE.md](LICENSE.md) for details.

## 🔗 Related Projects

- 📚 [Edumynt Literature](https://github.com/Edumynt/edumynt-literature) — Literary analysis and education
- ✍️ [Edumynt Grammar](https://github.com/Edumynt/edumynt-grammar) — English grammar guides
- 🌐 [Edumynt.in](https://edumynt.in) — Main landing page
- 📱 [Edumynt Blogs App](https://github.com/Edumynt/edumynt-blogs-app) — Mobile app (Android)

---

<p align="center">
  Built with ❤️ by <a href="https://edumynt.in">Edumynt</a> · <a href="https://github.com/Edumynt/edumynt-psychology">GitHub</a> · <a href="https://psychology.edumynt.in">psychology.edumynt.in</a>
</p>
