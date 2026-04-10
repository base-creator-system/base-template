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

## How It Works

BASE separates the app from its control.

- The Fan App is the user-facing app that you host and share  
- The Creator Dashboard is a control tool used to update your app  

The Creator Dashboard does not need to be hosted. It can be opened locally in a browser and used from any device.

Connection happens through:

- A public `content.json` URL (your hosted app data)  
- An access token (permission to update your repository)  

When connected, the dashboard updates your app remotely.

This means:

- Your app can be installed independently  
- Your control over it is portable  
- You are not tied to a platform or a specific device  

---

## Setup

BASE connects to a repository you control.

To use BASE, you will need:

- A public `content.json` URL  
- An access token for your repository  

In the Creator Dashboard:

1. Open `creator-Dashboard/index.html`
2. Enter your access token  
3. Enter your Content URL  
4. Click Publish  

---

## Repository Setup (Example: GitHub)

One way to set up your repository is using GitHub:

1. Create a repository  
2. Upload the "Fan App" folder  
3. Enable GitHub Pages  
4. Use your deployed `content.json` URL  

This is a default example. Any hosting setup that provides a public `content.json` URL can be used.

---

## Hosting Flexibility

BASE is host-agnostic.

The example above uses GitHub Pages because it is simple and widely available.

However, you may use any hosting provider (such as Netlify or others) as long as:

- Your `content.json` file is publicly accessible via a URL  
- The Creator Dashboard is configured with that URL  

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
