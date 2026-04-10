# BASE

BASE is a creator-owned system for publishing and controlling a personal app experience.

It is designed for creators who want direct ownership over how their content,
identity, and access are presented — without relying on centralized platforms.

---

## What BASE Is

- A personal app system (PWA-based)
- A creator-controlled publishing flow
- A structure for organizing content, media, and access
- A direct connection layer between creator and audience

---

## What BASE Is Not

- Not a platform
- Not a social network
- Not a marketplace
- Not a payment processor

BASE does not host or control creator revenue.  
It acts as a doorway to tools and systems chosen by the creator.

---

## Philosophy

Creators should not be dependent on platforms to exist.

BASE provides a foundation where:
- The creator owns the experience
- The creator controls distribution
- The creator defines access

---

## Structure (High-Level)

BASE consists of:

- Creator Dashboard — used to manage and publish  
- Fan App — the user-facing app experience  

The system is designed to remain flexible and host-agnostic.

---

## Setup

1. Create a GitHub repository

2. Upload the "Fan App" folder into your repository

3. Enable GitHub Pages:
   - Go to Settings → Pages
   - Set source to "Deploy from branch"
   - Select the main branch

4. Open the Creator Dashboard (index.html)

5. Enter:
   - GitHub Token
   - Content URL:
     https://YOUR-USERNAME.github.io/YOUR-REPO/Fan%20App/content.json

6. Click Publish

---

## Hosting Flexibility

BASE is host-agnostic.

The setup above uses GitHub Pages as a default because it is simple and widely available.

However, you may use any hosting provider (such as Netlify or others) as long as:

- Your `content.json` file is publicly accessible via a URL
- The Creator Dashboard is configured with that URL

In this case:
- Replace the Content URL with your own hosted URL
- Use the appropriate access method (API key, token, or deployment method) for your provider

BASE does not depend on any specific platform or hosting service.

---

## Usage

This system is open source under the MIT License.

You are free to:
- Use the code  
- Modify the system  
- Build your own version  

Use of this system is also subject to:

- Terms of Use → ./TERMS_OF_USE.md  

BASE is a system, not a platform.

---

## Author

William Smith McClinton  
Creator of BASE

---

## Status

BASE is an evolving system.

Core functionality is stable.  
Additional layers and tools may expand over time.
