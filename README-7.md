# boltnew.fun

AI-powered builder for websites, apps & prototypes — inspired by [bolt.new](https://bolt.new).

**Live site:** [https://boltnew.fun](https://boltnew.fun)  
**X / Twitter:** [@Bolt_newvc](https://x.com/Bolt_newvc)

---

## About

This is a high-fidelity landing page demo for an AI website & app builder experience. Users can type a prompt, explore the UI, and see a simulated build flow — designed for demonstration and portfolio use.

> Not affiliated with StackBlitz or the official bolt.new product.

---

## Features

- Modern dark UI (Inter font, responsive layout)
- Prompt box with Plan / Build actions
- Sign-in modal (Google & GitHub style)
- Building overlay simulation
- SEO-ready: Open Graph, Twitter Cards, JSON-LD
- Custom favicon, logo & OG image

---

## Repo structure

```
.
├── index.html              # Main landing page
├── CNAME                   # Custom domain → boltnew.fun
├── README.md
├── robots.txt
├── sitemap.xml
├── og-image.jpg            # 1200×630 social share image
├── logo.png                # Wordmark
├── logo-icon.png           # App icon 512×512
├── favicon.ico
├── favicon-32.png
├── favicon-48.png
├── favicon-96.png
├── favicon-192.png
└── apple-touch-icon.png    # 180×180 iOS
```

---

## Deploy (GitHub Pages)

1. Push this repo to GitHub.
2. **Settings → Pages → Source:** Deploy from branch `main` / root.
3. Ensure `CNAME` contains:

   ```
   boltnew.fun
   ```

4. Point your domain DNS:
   - **A records** → GitHub Pages IPs, or
   - **CNAME** → `bolt-new-dex.github.io` (or your username.github.io)

5. Wait a few minutes, then open [https://boltnew.fun](https://boltnew.fun).

### Validate social previews

After deploy, refresh caches:

- [Facebook Sharing Debugger](https://developers.facebook.com/tools/debug/)
- [Twitter Card Validator](https://cards-dev.twitter.com/validator)
- [LinkedIn Post Inspector](https://www.linkedin.com/post-inspector/)

---

## Local preview

Open `index.html` in a browser, or run a simple server:

```bash
# Python
python3 -m http.server 8080

# Node
npx serve .
```

Then visit `http://localhost:8080`.

---

## Credits

- Design inspired by [bolt.new](https://bolt.new) (StackBlitz)
- Built by [@Bolt_newvc](https://x.com/Bolt_newvc)

---

## License

MIT — free to use and modify for personal or commercial projects.  
Please keep the attribution to the original bolt.new concept where appropriate.
