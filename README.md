# Uniform MLE Explorer — Quant Story

**Live site:** [abo7mied.github.io](https://abo7mied.github.io)

An interactive derivation and exploration of Maximum Likelihood Estimation for the Uniform distribution, motivated by a quantitative finance problem.

## What's inside

- **Full MLE derivation** across all parameter cases (5 exhaustive cases with boxed results)
- **Live likelihood chart** — profile likelihood over θ with feasible region and MLE marker
- **Support endpoint chart** — see how changing θ moves the support boundaries
- **MLE invariance section** — downstream trading quantities (expected edge, hit probability, Q₀.₉₅, support width) derived by substitution
- **Interactive sliders** — adjust model parameters `a, b, c, d, n` and observed extremes in real time

## Math

The model is:

$$X_i \sim \operatorname{Unif}(a\theta + b,\; c\theta + d)$$

The MLE is a boundary estimator. The derivation covers all cases of `c − a` (positive, negative, zero, and degenerate).

## Deployment

This is a single `index.html` file. To publish on GitHub Pages:

1. Push `index.html` to the `main` branch of `abo7mied/abo7mied.github.io`
2. Go to **Settings → Pages → Source: Deploy from branch → main / root**
3. The site will be live at `https://abo7mied.github.io` within ~60 seconds

No build step. No dependencies to install. All libraries load from CDN (Chart.js 4.4.1, MathJax 3.2.2, Google Fonts).

---

*Ahmed Alzahrani*
