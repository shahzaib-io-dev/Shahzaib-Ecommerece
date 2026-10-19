# PCFORGE — Interactive Gaming PC Builder

> A complete WordPress + WooCommerce platform where users can configure, verify, and purchase custom gaming PCs in real-time.

[![Live Demo](https://img.shields.io/badge/Live-pcforge.com-55E6B5?style=for-the-badge)](https://pcforge.com)
[![Status](https://img.shields.io/badge/Status-Production-blue?style=for-the-badge)]()
[![License](https://img.shields.io/badge/License-All%20Rights%20Reserved-red?style=for-the-badge)]()

---

## 📖 Overview

PCFORGE is not just another ecommerce store — it's a **decision platform** built for PC enthusiasts who demand precision. Instead of scattered prices and confusing specs, users get an interactive experience: pick components, check compatibility in real-time, see FPS estimates, and add the entire build to cart with one click.

Built by a solo developer using **WordPress, WooCommerce, Elementor Pro, and custom PHP + JavaScript**.

---

## ✨ Key Features

### 🛠️ Interactive Build Lab
- 8-step guided PC configurator (CPU → GPU → RAM → Motherboard → SSD → PSU → Cooling → Case)
- **Real-time compatibility engine** — socket match, PSU wattage, RAM type validation
- **Live pricing** that updates as components are swapped
- **Performance estimates** — FPS projections for popular games (Cyberpunk, Valorant, GTA V, Elden Ring)
- **Live preview** — visual PC blueprint that activates components as they're selected
- One-click **"Add Complete Build to Cart"** via WooCommerce AJAX loop

### 🛒 Shop Page
- Products archive with **8-category sidebar filter** + live counts
- **Real-time search** with throttled input
- **Sort by** featured / price / name / rating
- **Price range** min-max filter
- **Availability filter** (in stock / on sale)
- **Wishlist toggle** with heart animation
- **Quick View modal** with dynamic product data
- Auto-generated **product badges** (Sale %, NEW, HOT, OUT)
- **Skeleton loading** state + empty state
- **Pagination** (12 products per page)

### 🎨 Custom Design System
- "Forge Mint" color palette — obsidian dark + ember mint accent (#55E6B5)
- **Terminal/HUD-inspired aesthetic** with CRT scanlines
- Custom fonts — Space Grotesk (headings), Inter (body), JetBrains Mono (mono)
- **Glassmorphism** cards with backdrop blur
- **Micro-interactions** everywhere — hover states, magnetic cursor, animated buttons

### 🌐 Global Components
- **Header** — glassmorphism, mega menus, live product count, cart icon with real-time sync, magnetic CTA button
- **Footer** — aurora background, newsletter with OTP verification, brand-colored social links, animated back-to-top button
- **Preloader** — BIOS boot sequence with ASCII logo and component detection log

### 📬 Contact Page
- Terminal-style form with `> prompt` per input
- **3D tilt cards** on mouse move
- **Live system diagnostics** panel (signal, latency, uptime simulation)
- **Real WordPress AJAX** submission with SendLayer SMTP
- **Terminal loader** sequence (ENCRYPTING → ROUTING → TRANSMITTING → SECURING)
- **Scramble text** success overlay
- FAQ accordion in "System Logs" theme

### 📧 Newsletter System
- **3-stage flow**: Email → OTP → Success
- Real **WordPress AJAX** with transient-based OTP storage (10-min expiry)
- **SendLayer SMTP** integration via WP Mail SMTP Pro
- 6-digit OTP input with auto-focus, paste support, 30s resend timer
- Admin panel to view subscribers + CSV export
- Shared state (localStorage) between home page and footer

### 👤 About Page
- Full-screen hero with **typewriter effect**
- **Animated background** — 3 floating orbs, grid parallax, 120 canvas stars
- **Interactive forge logo** — moves on scroll, auto-rotates after idle, explodes into 30 particles on click
- Mission, Values, Stats (animated counters), Story timeline, FAQ sections
- **"The Architect"** — developer profile section
- Custom cursor glow throughout

---

## 🛠️ Tech Stack

| Layer | Technologies |
|-------|-------------|
| **CMS** | WordPress 6.5+ |
| **Ecommerce** | WooCommerce 11.2 (Store API + AJAX Cart) |
| **Page Builder** | Elementor + Elementor Pro |
| **Theme** | Hello Elementor (lightweight) |
| **Frontend** | HTML5, CSS3 (custom properties, grid, animations), Vanilla JavaScript |
| **Canvas/SVG** | Particle systems, network graphs, custom icons |
| **Backend** | PHP 8.0+, WordPress AJAX, Transients API |
| **Email** | WP Mail SMTP Pro + SendLayer |
| **Development** | Local by Flywheel |

---

## 📁 Project Structure
