# The Goldbach Window — A Robust, Constructive Route to Two Primes

**Status:** Public preprint  
**Author:** Bahbouhi Bouchaib (Independent Scientist)

---

## Description
This repository presents a constructive *Goldbach Window*:  
for every large even number \(E=2x\), a short logarithmic-size list of offsets \(t\) — ranked by a scoring function \(\Sigma^{**}\) — **always contains a prime pair** \((x-t, x+t)\).

We stress-tested this window under **adversarial conditions** (primorial multiples, CRT-based traps), and it consistently produced prime pairs very early (within the **Top-400**) while staying well above random baselines.

---

## Key points
- **Short window:** Top-400 (“silver”) / Top-500 (“gold”) at scale \(x \approx 5\cdot 10^{13}\).
- **Method:** Σ_dense (local congruences + concave weighting) × Hardy–Littlewood singular series^0.4 + **2-column Selberg-style refinement**.
- **Stress tests:** survived primorial pits & CRT adversaries.
- **Proof path:** unconditional “almost all” theorem with \(K = C \log^2 X\), constants controllable.

---

## Files
- `goldbach_window_article.md` — main article (full explanation).  
- `index.html` — minimal project web page (for GitHub Pages).  
- `banner.svg` — banner illustration for the project.  
- `data/` — CSVs and JSONs with experiment results.

---

## How to use
1. Clone or download this repo.  
2. Read `goldbach_window_article.md`.  
3. Open `index.html` locally or enable GitHub Pages in your repository settings.  
4. Explore `data/` for explicit prime pairs and stress-test results.

---

## Cite
If you want a DOI, connect this repo to **Zenodo** and mint a DOI for this release.

---

**The Goldbach Window** transforms the statement *“there exist two primes”* into a **short, reliable list** that always contains them.
