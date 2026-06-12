Here is a clean, professional, and beautifully structured `README.md` file for your **Cozy-Core Creative Studio / Gallery Portfolio** website. It is designed to look polished for your GitHub repository, showcasing both the design architecture from your blueprint and the aesthetic implementation.

---

# ✦ Digital Artsy — Cozy Creative Studio Portfolio

A beautiful, static visual archive and portfolio website designed for digital artists. Built with an emphasis on **visual architecture, geometric consistency, and a soothing "cozy-core" aesthetic**, this responsive web design maps directly to a structured 12-column engineering blueprint.

---

## Theme & Visual Identity

The project implements a **Whimsical Cozy-Core Studio** theme, trading harsh digital contrast for organic, warm, and comforting tones.

* **Color Palette:**
* Background: Warm Cream (`#faf6f0`)
* Typography: Deep Espresso Charcoal (`#2e2520`)
* Accents: Soft Sage Green (`#90a98f`) & Muted Terracotta (`#dd8e75`)


* **Typography:**
* Headings: Elegant, literary serif (*Lora*)
* Body Text: Soft, highly legible geometric sans-serif (*Nunito*)


* **Micro-interactions:** Smooth, lightweight floating card lift mechanics utilizing fine-tuned `cubic-bezier` transitions and soft, expansion inner box shadows.

---

##  Structural Architecture (Blueprint Specifications)

The interface translates exact rigid engineering wireframe parameters into fluid, responsive front-end components:

| Component | Blueprint Design Metric | CSS Implementation |
| --- | --- | --- |
| **Global Width** | Max Content Boundary: `1200px` | `max-width: 1200px; margin: 0 auto;` |
| **Header Banner** | Fixed Block Height: `80px` | `height: 80px; position: fixed;` |
| **Hero Section** | Layout Scope: `100vh` Viewport | `min-height: 100vh; padding: 120px 0;` |
| **Grid Layout** | Standard 12-Column Template | `display: grid; gap: 24px;` |
| **Layout Gutter** | Linear Separation: `24px` | `gap: 24px;` (Grid spacing parameter) |
| **Module Frames** | Consistent Proportional Target | `aspect-ratio: 4 / 5; object-fit: cover;` |
| **Footer Section** | Container Height: `400px` | `height: 400px; margin-top: 60px;` |

---

##  Repository Structure

```text
├── index.html          # Main single-file source containing HTML5 structural layout
├── assets/             # Media and image subdirectory
│   ├── cat.png         # "Sunbasking" card asset
│   ├── citrus.png      # "Citrus Orchard" card asset
│   ├── figs.png        # "Midnight Fig" card asset
│   └── logo.svg        # Custom minimalist site vector signature
└── README.md           # Documentation layout repository profile

```

---

##  Technical Highlights

### 1. Unified Card Layout Engine

Resolves horizontal runaway container bugs by strictly binding image scaling to structural flexbox vectors (`flex-direction: column`). It ensures the layout stacks perfectly across all tablet and viewport variations.

### 2. Distortion-Free Asset Scaling

Leverages the native CSS properties `aspect-ratio` and `object-fit: cover`. Images act as a physical picture frame, maintaining standard visual consistency across the entire gallery grid regardless of the original uploaded image file dimensions.

### 3. Glassmorphism Dynamic Header

The persistent `80px` navigation top-bar features high-performance background filtering (`backdrop-filter: blur(5px)`) layered over translucent cream hues, allowing the content grid to scroll underneath smoothly without jarring visual breaks.

---

## Deployment & Local Setup

Since this layout runs on native vanilla architectures, it requires no compilation overhead, node modules, or external bundling pipelines.

1. **Clone the repository:**
```bash
git clone https://github.com/yourusername/digital-artsy-portfolio.git

```


2. **Navigate into the directory:**
```bash
cd digital-artsy-portfolio

```


3. **Execute the workspace:**
* Double-click `index.html` to open it directly inside any modern web browser.
* Alternatively, spin up a local development sync environment via VS Code's **Live Server** extension.
