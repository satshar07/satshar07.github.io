# Satyam Sharma  
**UC Berkeley — Computer Science + Operations Research**

[Email](mailto:satyam_sharma@berkeley.edu)

---

## About
I’m interested in making models and systems work under real constraints. Most of my work has been about testing ideas that sound good on paper and figuring out which ones actually hold up when you try to use them.

My background spans deep learning, computer vision, and mission-facing software, with a bias toward practical signal over theoretical elegance.

---

## Research & Projects

### Optimization: Dynamic Hyperparameter Updates
I worked on a deep learning project exploring whether updating hyperparameters *during* training meaningfully improves outcomes.

- Looked at methods like Population-Based Training and hypergradient-based updates.
- What stood out was how often these methods quietly optimize for short-term stability rather than long-term performance.
- In constrained settings, strong static baselines were consistently harder to beat than expected.

The most useful takeaway wasn’t a new algorithm, but a clearer sense of **when adaptive optimization ideas are worth the complexity and when they aren’t**.

---

### Computer Vision: EnsembleGold (Monocular Depth Estimation)
A focused computer vision project improving diffusion-based monocular depth estimation at inference time.

- Built on a Marigold-style diffusion pipeline for relative depth prediction.
- Made only inference-time changes: ensemble sampling across diffusion runs, simple affine alignment, and denoising schedule tweaks.
- These changes consistently reduced error across standard depth metrics.
- Most notably, Squared Relative Error dropped by ~17% relative to the baseline, with smaller but steady gains elsewhere.

What I liked about this project was that all improvements came from **how the model was used**, not retraining or architectural changes.

---

### Defense Software Deployment: Second Front Systems
Work focused on understanding why strong commercial software struggles to reach operational use inside the DoD.

- Examined deployment bottlenecks around accreditation, security review, and procurement.
- Focused on speed-to-deployment as a first-class constraint rather than an afterthought.
- Learned that deployment infrastructure and compliance tooling often matter more than marginal performance improvements.

This work reshaped how I think about “shipping” in mission-critical contexts — deployment pathways are part of the product.

---

### National Security Entrepreneurship DeCal (Founder & Instructor)
I founded and ran Berkeley’s National Security Entrepreneurship DeCal.

- Designed the course around real deployment and adoption constraints, not abstract defense-tech narratives.
- Led multiple client-backed student projects, including work connected to Second Front Systems.
- Took full ownership of course structure, pacing, and external coordination.

The hardest part wasn’t content — it was building a system that forced realism without killing momentum.

---

## Technical Stack
- **Core:** Python, PyTorch, C, Java, SQL  
- **Research:** Qiskit, PennyLane, Weights & Biases, LaTeX  
- **Systems / Ops:** GitHub Actions, Palantir Foundry  

---

## Experience
- **Moelis & Company** — Technology M&A Summer Analyst  
- **Industry Ventures** — AI Secondaries Analyst  
- **Instacart** — Internal Python-based data tooling  
