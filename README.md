<<<<<<< HEAD
# Whistle Aligners — Frontend Assessment

## Setup & Run

```bash
npm install
npm start
```

App runs at `http://localhost:3000`

---

## All Sections Built (matching Figma/design)

| Section | Description |
|---|---|
| **Hero** | Headline, radio inputs, booking form, Clove Dental badge |
| **Marquee** | Scrolling promo banner (CSS animation) |
| **Dream Smiles** | Two-col layout with Whistle Aligner product card |
| **Results You'll Love** | 4-col grid with API data + skeleton loading + error state |
| **Why Whistle?** | 4 feature cards with images and hover effect |
| **The Whistle Difference** | Dark background, 3 key points with image |
| **Comparison Table** | Whistle vs Other Brands with ✓/✗ indicators |
| **Four Simple Steps** | Numbered steps with image |
| **Doctor-Led** | Split layout with CTA button |
| **Happy Smilers** | Dark purple section with patient photo grid |
| **FAQ** | Expand/collapse accordion (interaction) |
| **Footer** | 4-col footer with links and social |

---

## API Used

**DummyJSON** — `https://dummyjson.com/products?limit=8`

Used in the "Results You'll Love" section. Product IDs seed placeholder images via `picsum.photos`. Loading state shows skeleton cards; errors show a retry button.

---

## Interactions

- **FAQ Accordion** — expand/collapse, one open at a time
- **Result Cards** — hover lift + shadow
- **Why Whistle cards** — hover lift effect
- **Happy Smilers** — hover zoom on images

---

## Approach

Matched Whistle's clean, minimal aesthetic — off-white backgrounds, soft purple accents, Fraunces display font for headings paired with DM Sans for body. All components are functional components using hooks. CSS is plain per the assessment requirements (no UI libraries). Images use `picsum.photos` seeded URLs to match proportions from the Figma design.
=======
# whistle-react-frontend-assessment
Frontend Developer Assessment for Unbundl built with React.js and Vite. Developed responsive UI based on Figma design with dynamic data integration using DummyJSON API, loading and error handling, and interactive components.
>>>>>>> 306c82bd93f71f62662be46af26f4035bffd6295
