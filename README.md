# NeoNix Quantitative Research & Systems Lab
*Institutional Portfolio & Research Showcase (`https://neonix-lab.github.io`)*

This repository hosts the static portfolio, architectural manifests, and empirical research tear sheets for **NeoNix Quantitative Lab**, showcasing the methodologies, invariants, and causal trading architectures built in [`NeoNix-Lab/quant-platform`](https://github.com/NeoNix-Lab/quant-platform).

---

## Architecture & Technology Stack

- **Framework**: [Astro v7](https://astro.build/) (Static Site Generation, zero runtime JS bloat).
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com/) with custom slate dark-theme design tokens.
- **Typography**: Inter (Prose) & JetBrains Mono (Financial metrics, decimal invariants, and code).
- **CI/CD**: GitHub Actions deploying to GitHub Pages via `withastro/action`.

---

## Local Development

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build static output for production
npm run build

# Preview build locally
npm run preview
```
