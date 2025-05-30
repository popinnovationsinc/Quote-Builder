_Built with ❤️ by Josh Brown._

## Thanks for Checking Out My Quote Builder!
This is a lightweight tool that works in your web browser. I converted it from one of my web applications I developed in 2024 for a small business. The purpose of it is to help anyone quickly generate repair estimates, without the depression and clunkiness that comes with using spreadsheets.
With this app, you can:
- **Dynamically create text-based repair estimates**    
  - Add, reorder, and quickly duplicate an unlimited number of line items
  - Auto-calculate parts & labor taxes, shop-supplies charges, shipping, and include current bill adjustments
  - Instantly calculate retail pricing via the “Magic Box” engine
- **Generate two quotes simultaneously**: **Recommended** _and_ **Required**
- **Export/import your settings** (excluding hourly labor rates) to `.txt` (plain-text JSON)

I built this app using a blend of tools - **Vanilla JS**, **Bootstrap 5**, **SortableJS**, and **Font Awesome 6**.  
All settings persist in your browser’s `localStorage`.

---

## 🚀 Getting Started

1. **Clone** this repo:  
   ```bash
   git clone https://github.com/popinnovationsinc/Quote-Builder.git
2. **Open in your web browser**:
   - To run the app, locate the project's _index.html_, and double-click the file, or you can drag-and-drop it into any web browser window.
   - **Please note:** This project is _dependent_ on bootstrap's CSS and fontawesome - _you will need an internet connection for the application to work properly_. **Please reference "🚧 Upgrading Safely & Storing Settings" below.**
---

## 🎉 Consider Supporting Me

If you like the app I've created, keep me motivated and buy me a coffee!

[![Buy Me a Coffee](https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png)](https://www.buymeacoffee.com/imjoshbrown)  
<small>(or visit <https://www.buymeacoffee.com/imjoshbrown>)</small>

---

## 💻 Looking for More / Want to Collaborate? Sweet!

I’m a **full-stack web-application developer** (TALL stack: Tailwind, Alpine.js, Laravel, Livewire).  
If you’d like to evolve Quote Builder into a cloud-hosted app, with user accounts, team sharing, invoicing, or more - please reach out!

- **Instagram:**  
  [![Instagram @imjoshbrown](https://img.shields.io/badge/Instagram-@imjoshbrown-405DE6?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/imjoshbrown)  
- **Email:**  
  [![Email Me](https://img.shields.io/badge/Email-sands--81.crampon%40icloud.com-blue?style=for-the-badge&logo=gmail)](mailto:sands-81.crampon@icloud.com)

## 🚧 Upgrading Safely & Storing Settings

> **Everything you configure—General Presets, Price Models & Hourly Labor Rates—lives only in your browser’s `localStorage`.**  
> Clearing cookies/site-data or loading a fresh copy will erase **all** your settings.

Backing up is **critical**, but easy:

1. **General Presets**  
   - Go to the **General Presets** tab.  
   - Click **Export General Presets** ⇒ download a `.txt` (JSON).  
   - After upgrading, re-import with **Import Presets**.

2. **Price Models**  
   - Switch to the **Price Models** tab.  
   - Click **Export Price Model** on any row ⇒ download its `.txt`.  
   - Re-import via **Import Price Model**.

3. **Hourly Labor Rates**  
   - _No export button._  
   - If lost, recreate under **Manage Presets → Hourly Labor Rates → Create New Hourly Labor Rate**.

> **Tip:** Store these JSON files in a safe place (cloud drive, password vault, etc.). A single import restores your entire workspace. 
