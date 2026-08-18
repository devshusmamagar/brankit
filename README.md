# SHUSMA Brand Kit

> Complete brand identity system for **SHUSMA READymADE GARMENTS TRADING L.L.C**
> Women's Luxury Fashion Ecommerce | Mobile-first | Bilingual (English + Arabic)

---

## Brand Overview

| Property | Value |
|---|---|
| **Brand Name** | SHUSMA |
| **Legal Entity** | SHUSMA READymADE GARMENTS TRADING L.L.C |
| **Arabic Name** | شوسما لتاجر الملابس الجاهزة ش.ذ.م.م |
| **Industry** | Women's Fashion Ecommerce — Readymade Garments |
| **Specialization** | Designer Jeans, T-Shirts, Blazers, One-Pieces, Kurtas, Suits, Shoes & Accessories |
| **Design Philosophy** | Mobile-first, all display resolutions |
| **Languages** | English (LTR) + Arabic (RTL) |
| **Generated With** | [open-design](https://github.com/nexu-io/open-design) by nexu-io |

---

## Product Categories

SHUSMA specializes in women's readymade garments and accessories:

| Category | Description |
|---|---|
| **Designer Jeans** | Premium denim collection — straight, slim, wide-leg, and flared fits |
| **T-Shirts** | Designer cotton tees — casual, oversized, and fitted styles |
| **Blazers** | Tailored blazers — structured, relaxed, and oversized silhouettes |
| **One-Pieces** | Dresses, jumpsuits, and rompers — casual to formal |
| **Kurtas & Suits** | Ethnic wear — embroidered kurtas, coord sets, and suit sets |
| **Shoes** | Heels, flats, sandals, and designer footwear |
| **Designer Pieces** | Limited-edition statement garments and exclusive collections |

---

## Color Palette

| Color | Hex | Usage |
|---|---|---|
| Primary Gold | `#C9A961` | CTAs, accents, decorative elements |
| Dark Gold | `#A07D3F` | Secondary buttons, hover states |
| Light Gold | `#E2CC8A` | Highlights, decorative fills |
| Cream | `#FAF8F5` | Page backgrounds |
| Brown | `#5D4E37` | Secondary text, dark elements |
| Dark | `#1A1A1A` | Primary text, dark mode base |

---

## Typography

| Role | Font | Weight |
|---|---|---|
| English Headings | Playfair Display | 500, 600, 700 |
| English Body | Inter | 300, 400, 500, 600 |
| Arabic Headings | Noto Serif Arabic | 400, 600, 700 |
| Arabic Body | Noto Sans Arabic | 300, 400, 500, 600 |

---

## Brand Kit Structure

```
brankit/
├── vector-logo/              # Source SVG files + vector analysis
│   ├── 1.svg                 # Primary logo SVG (mixed vector + raster)
│   ├── 2.svg                 # Secondary logo SVG (raster in SVG wrapper)
│   └── vector-analysis.md    # Detailed SVG structure analysis
├── 01-logo/
│   ├── primary/              # Primary & full logo variants
│   ├── secondary/            # Horizontal lockup
│   ├── icon/                 # Icon-only version
│   ├── favicon/              # 16–256px favicons + .ico
│   ├── monochrome/           # Black, white, gold versions
│   ├── reversed/             # Dark background versions
│   └── app-icon/             # 1024px app icons (light + dark)
├── 02-color-system/          # Full color palette documentation
├── 03-typography/            # Type system with specimens
├── 04-graphics-kit/
│   ├── patterns/             # 8 SVG pattern library
│   ├── textures/             # Damask, linen, leather, silk
│   ├── icons/                # 12 ecommerce icon set
│   ├── ornaments/            # Decorative dividers & accents
│   └── dividers/             # Section break dividers
├── 05-brand-architecture/    # Brand platform, personas, positioning
├── 06-error-pages/          # 404, 500, maintenance pages
├── 07-email-templates/      # Welcome, order, cart, promo emails
├── 08-social-media/
│   ├── instagram/            # Post & carousel templates
│   ├── facebook/             # Cover photo
│   ├── twitter/              # X header banner
│   ├── whatsapp/             # Status template
│   ├── stories/              # Instagram story template
│   └── social-media-guide.html
├── 09-packaging/            # Bags, boxes, stationery, guide
├── 10-accessibility/        # WCAG 2.1 AA compliance guide
├── 11-marketing-templates/  # Sale, loyalty, gift cards, signage
├── 12-admin-console/        # Full admin UI component kit
├── 13-onboarding/           # App onboarding screens & guide
├── 14-screens/              # Ecommerce UI screens (8 pages)
├── 15-brand-images/         # Lifestyle photos & photography guide
├── 16-product-categories/   # Women's fashion category images
├── SHUSMA_Brand_Guidelines.html  # Master brand guidelines
├── SHUSMA_Brand_Guidelines.pdf   # PDF version
├── index.html               # Interactive brand kit browser
└── README.md                # This file
```

---

## What's Included

### Logo System (01-logo)
- **Primary Mark**: Full vertical logo lockup with ornate frame
- **Full Logo**: Complete branding with Arabic & English text
- **Full Logo Alt**: Alternative version from second SVG
- **Horizontal Lockup**: Secondary horizontal logo variant
- **Icon**: Cropped center mark for small sizes
- **Favicons**: 16px, 32px, 48px, 64px, 128px, 192px, 256px + ICO bundle
- **Monochrome**: Black, white, and gold single-color versions
- **Reversed**: On dark (#1A1A1A) and brown (#5D4E37) backgrounds
- **App Icons**: 1024×1024 with rounded corners (dark + light variants)

### Vector Logo Analysis (vector-logo/)
- **1.svg**: Mixed vector (70 paths) + 14 embedded PNG images
- **2.svg**: Raster image wrapped in SVG (1 path + 1 large 670KB PNG)
- **Neither is pure vector** — see `vector-analysis.md` for full technical breakdown
- All PNG variants generated at high quality from these source files

### Color System (02-color-system)
- 6 brand colors + 5 semantic colors with full specs
- Tint & shade scales, 8 gradient presets
- WCAG contrast ratio matrix, dark mode adaptation
- Print CMYK values & Pantone approximations
- Complete CSS custom properties

### Typography (03-typography)
- 4 font families (English + Arabic)
- Modular type scale (12px–72px), responsive breakpoints
- RTL Arabic specimens, ecommerce type specs

### Graphics Kit (04-graphics-kit)
- 8 SVG patterns, 4 premium textures
- 12 ecommerce icons (gold + dark), 7 ornaments, 5 dividers

### Brand Architecture (05-brand-architecture)
- Mission, Vision, Values, personality, voice
- 3 target personas, positioning, touchpoint map

### Error Pages (06-error-pages)
- 404 (animated), 500 (dark), maintenance mode

### Email Templates (07-email-templates)
- Welcome (bilingual), order confirmation, abandoned cart, promotional
- Table-based, 600px, email-client compatible

### Social Media (08-social-media)
- 6 platform images + comprehensive guide

### Packaging (09-packaging)
- 4 product images + full specification guide

### Accessibility (10-accessibility)
- WCAG 2.1 AA guide, 35+ item checklist, ARIA patterns

### Marketing Templates (11-marketing-templates)
- 8 HTML/CSS mockups + 3 generated images

### Admin Console (12-admin-console)
- 15-component UI kit with dark sidebar

### Onboarding (13-onboarding)
- 4 screens + animation specs + bilingual text

### Ecommerce Screens (14-screens)
- 8 mobile-first HTML pages

### Brand Images (15-brand-images)
- 5 editorial photographs + photography style guide

### Product Categories (16-product-categories)
- 7 category images: Jeans, T-Shirts, Blazers, One-Pieces, Kurtas & Suits, Shoes, Designer Pieces

---

## Usage

1. **Clone** this repository
2. Open `index.html` in a browser to browse the full brand kit
3. Check `vector-logo/vector-analysis.md` for SVG technical details
4. Copy CSS variables from color/typography systems into your project
5. Use PNG assets directly in your application
6. Reference SVG code from graphics kit for inline icons
7. Follow brand guidelines for consistent application

---

## Tech Stack

- **[open-design](https://github.com/nexu-io/open-design)** — Brand generation framework by nexu-io
- **HTML5/CSS3** — All templates are self-contained
- **Google Fonts** — Playfair Display, Inter, Noto Serif Arabic, Noto Sans Arabic
- **SVG** — Inline scalable graphics
- **CairoSVG + Pillow** — Logo variant generation pipeline
- **AI Image Generation** — Brand photography and category images

---

## Brand Values

1. **Craftsmanship** — Meticulous attention to detail in every piece
2. **Elegance** — Timeless sophistication in design and experience
3. **Inclusivity** — Fashion for every woman, every occasion
4. **Heritage** — Rooted in tradition, looking toward the future
5. **Innovation** — Modern ecommerce meets luxury retail

---

## License

This brand kit is proprietary to **SHUSMA READymADE GARMENTS TRADING L.L.C**.
All rights reserved.

---

*SHUSMA READymADE GARMENTS TRADING L.L.C*
*شوسما لتاجر الملابس الجاهزة ش.ذ.م.م*