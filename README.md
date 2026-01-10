# Satyam Sharma  
**UC Berkeley — Computer Science + Operations Research**

[Email](mailto:satyam_sharma@berkeley.edu)

---

## About
I’m interested in making models and systems work under real constraints. Most of my work has been about testing ideas that sound good on paper and figuring out which ones actually hold up when you try to use them.

My background spans deep learning, computer vision, and mission-facing software.

---

## Research & Projects

### Dynamic Hyperparameter Optimization (Vision Transformers)
Research project under a robotics PI evaluating whether online hyperparameter updates outperform strong static baselines.

- Studied Population-Based Training and hypergradient-style updates (the online hyperparameter methods)
- Found that lightweight online methods often converge to overly conservative regimes
- In constrained compute settings, well-tuned static baselines consistently matched or outperformed adaptive methods
- Main contribution was identifying *why* these methods fail quietly: short-horizon optimization, population stratification, and insufficient adaptation time

This project was less about proposing a new optimizer and more about stress-testing popular ideas under realistic constraints. Pending publication.

---

### EnsembleGold — Monocular Depth Estimation
Inference-time improvements to diffusion-based monocular depth estimation.

- Built on a Marigold-style diffusion pipeline
- Introduced ensemble consensus sampling and per-scene affine alignment
- No retraining or architectural changes
- Achieved a ~17% reduction in Squared Relative Error on NYU-Depth V2, with consistent gains across other metrics

All improvements came from inference-time decisions, not model capacity.

---

### Defense Software Deployment — Second Front Systems
Sourced and worked with 2FS, a DoD‑accredited platform supporting up to TOP SECRET environments, and built an agentic system for vulnerability remediation in defense software environments. Work was shouted out at their quarterly investor meeting. 

- The system ingests SBOMs and vulnerability findings, normalizes them, and proposes concrete remediation actions
- Focused on the **agentic remediation engine**. Designed remediation logic that reasons over dependency graphs and produces actionable changes (e.g., package upgrades, Dockerfile edits) rather than generic advisories
- Work was grounded in deployment realities: compliance constraints, reproducibility, and auditability

The project treated remediation as a systems problem, not a classification task.
---

### Falkonry — Adversarial Time-Series & State Inference (Electronic Warfare)
Worked on ML systems for **electronic warfare and jamming environments** embedded in Falkonry’s platform.

- The core problem was **latent state inference under adversarial distribution shift**, not standard time-series forecasting
- Modeled time-series signals where changes are driven by **intentional interference and adaptation**, not stochastic noise
- Built representations over multi-scale temporal features to infer regime changes, operational states, and adversary behavior
- Operated with delayed or partial ground truth, requiring robustness to label uncertainty and non-stationarity
- Central challenge was distinguishing **structured behavior from deception**, not anomaly detection

This work pushed beyond classical time-series ML toward **robust inference in adversarial, non-stationary environments**.

---

## Technical Skills
Python, PyTorch, NumPy  
Distributed training concepts, mixed precision, and experiment tracking  
Diffusion models, inference-time ensembling, sampling strategies  
Optimization dynamics and hyperparameter sensitivity  
Time-series modeling under non-IID and adversarial shift  
Agentic systems, graph-based reasoning, reproducible pipelines

