# Mishal’s Global Digital Network
### A premium interactive concept by JARVIS Agency

A responsive standalone HTML prototype exploring a connected café-brand experience: global discovery → markets → café pages → franchise enquiries, with a local-only location-management concept.

> **Concept disclaimer:** This is an independent illustrative prototype prepared by JARVIS Agency for evaluation. It is not an official Mishal’s product, is not affiliated with or endorsed by Mishal’s, and is not connected to any production systems.

## Features
- Premium responsive homepage and mobile navigation
- Market discovery for United Kingdom and Pakistan
- Individual example café pages
- Client-side search and filtering
- Directions links (confirm addresses before real-world use)
- Validated franchise/expansion demo form; no data is sent
- Location management concept: search, status filters, edit, save and cancel
- Responsive layouts, focus styles, accessible labels and reduced-motion support
- No build step, package install, API key or backend required

## Run locally
1. Download or clone the repository.
2. Open `index.html` in a modern browser, or open the folder in VS Code.
3. Optional: use the VS Code **Live Server** extension.

## Deploy to GitHub Pages
A GitHub Actions workflow is included.
1. Create a GitHub repository and push these files to the `main` branch.
2. Open **Settings → Pages**.
3. Under build and deployment, choose **GitHub Actions** if prompted.
4. Wait for the workflow to finish; open the URL shown in the Pages deployment.

## Demo routes
| Route | Purpose |
|---|---|
| `#/` | Global homepage |
| `#/markets` | Market and location discovery |
| `#/markets/uk` | United Kingdom concept |
| `#/markets/pakistan` | Pakistan concept |
| `#/locations/slough` | Example café page |
| `#/locations/mm-alam-road` | Example café page |
| `#/locations/lake-city` | Example café page |
| `#/franchise` | Demo enquiry form |
| `#/manage/locations` | Local-only management concept |

## Important content and asset notes
- Location names and details are examples for concept evaluation. Verify status, addresses, opening hours, phone numbers, menus and services with official sources before public or customer use.
- The app does not claim live integrations, actual enquiry delivery, authentication, analytics, ordering, payment, or production data management.
- Photography is illustrative remote imagery loaded from Unsplash URLs. Internet access is needed; check asset terms and availability before public/commercial deployment.
- The provisional palette and copy are concept choices, not official brand guidelines.
- The enquiry form does not transmit or persist submitted data. Management edits exist in page memory and reset on reload.
- This is a static HTML/CSS/JavaScript prototype with no build/test framework.

## Before publishing
- [ ] Confirm permission to use the brand name and assets.
- [ ] Verify all public-facing location information.
- [ ] Replace illustrative images with approved/licensed assets as needed.
- [ ] Review privacy, accessibility, legal and brand requirements.
- [ ] Test links and interactions on current mobile and desktop browsers.
- [ ] For real enquiries, add an approved backend, privacy notice, spam protection and security controls.
- [ ] For real administration, add authentication, authorization, audit history, server-side validation and secure storage.

## Git commands
```bash
git init
git add .
git commit -m "Initial Mishal's digital network concept"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/mishals-global-digital-network.git
git push -u origin main
```
Replace `YOUR-USERNAME` with your GitHub username and create the remote repository first.

## Maintainer
**JARVIS Agency** — concept prototype.
