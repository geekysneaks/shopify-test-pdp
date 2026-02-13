# Shopify Product Page Redesign - Technical Test by Folaju Oyegbesan

I built a custom Shopify product page that matches Nomad's premium look and feel. The goal was to create something that feels polished and works seamlessly, while staying flexible enough for store owners to customize without touching code.

## 🎯 What I Set Out To Do
Transform Shopify's standard Dawn theme into an interactive, premium shopping experience. Think dynamic product storytelling, smooth variant switching, and a design that actually feels crafted—not templated.

---

## 🚀 What I Built

### 1. Premium Color Swatches
Instead of boring dropdown menus, I created circular color swatches that feel tactile and intuitive.

**How it works**: The system pulls from Shopify's swatch data when it's there, and falls back to smart CSS defaults for common colors like Black or Navy. Each swatch has a subtle inner border when selected and shows a tooltip on hover—small touches that make it feel high-end.

### 2. Instant Variant Image Updates
Nobody likes waiting for pages to reload just to see a different color. So I built a system that switches product images instantly when you pick a new variant.

**The technical bit**: Instead of reloading the entire page, the gallery filters images based on what matches the selected color. It's smooth, fast, and keeps shoppers engaged.

### 3. Flexible Storytelling Banners
This was the fun part. I created a banner system that lets you tell your product's story in two ways:

- **Split layout**: Perfect for combining a great product shot with some compelling copy
- **Full-width hero**: When you need maximum visual impact

Store owners can customize these through Shopify metafields—no code required. Just upload images and add text through the admin panel.

### 4. Smart Navigation Pills
I added a sticky navigation bar that helps people explore the page without getting lost.

**The details**: It sticks to the top as you scroll, smoothly jumps to different sections (Overview, More Info, FAQ), and highlights which section you're currently viewing. It's one of those features that users don't consciously notice but makes everything feel more polished.

### 5. Horizontal Product Recommendations
Redesigned the "you might also like" section to match Nomad's clean aesthetic. Instead of generic product cards, these are sleek horizontal cards with rounded corners and subtle shadows—placed right where people naturally look after checking out the main product.

---

## 🛠 How I Built It

**Performance first**: I kept everything vanilla—minimal JavaScript, clean CSS, optimized Liquid templates. The page loads fast and scores well on Core Web Vitals.

**Metafield-driven**: Store owners can customize everything through Shopify's admin interface. Want to change a banner? Update it in the product settings. No developer needed.

**Responsive by default**: Every component works beautifully on phones, tablets, and desktops. I tested extensively to make sure nothing breaks at any screen size.

---

## 📖 Getting It Running

### Setting Up Metafields
You'll need to create these in **Settings > Custom Data > Products**:
- `custom.banner_image_1` - Upload banner images here
- `custom.banner_heading_1` - Banner headline text
- `custom.banner_text_1` - Supporting copy for banners
- `custom.info_accordion` - Additional product info
- `custom.related_products` - Handpick recommended products

### Installing the Theme Components
- Drop the "PDP Nav Pills" section into your product template
- Add the "Bottom PDP Accordions" section at the bottom
- Configure your FAQ questions right in the section settings

---
  



