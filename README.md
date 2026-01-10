# Satyam Sharma  
**UC Berkeley — Computer Science + Operations Research**

[Email](mailto:satyam_sharma@berkeley.edu)
---
<style>
  .two-col {
    display: flex;
    gap: 2.5rem;
    align-items: flex-start;
  }
  .col {
    flex: 1;
    min-width: 320px;
  }
  @media (max-width: 900px) {
    .two-col { flex-direction: column; }
  }
  .tldr {
    font-weight: 600;
    margin: 0.25rem 0 0.75rem 0;
  }
</style>

<div class="two-col">
  <div class="col" markdown="1">
    
## Research

### Dynamic Hyperparameter Optimization (Vision Transformers)
**TLDR:** Showed why popular online hyperparameter methods often underperform strong static baselines under realistic compute constraints.

Research project under a robotics PI evaluating Population-Based Training and hypergradient-style updates for Vision Transformers. Found that many adaptive methods converge to conservative regimes due to short-horizon optimization, population stratification, and insufficient adaptation time. Pending publication.

---

### EnsembleGold — Monocular Depth Estimation
**TLDR:** Improved diffusion-based depth estimation using inference-time techniques only.

Built novel inference-time improvements on a Marigold-style diffusion pipeline, including ensemble consensus sampling and per-scene affine alignment. Achieved ~17% reduction in Squared Relative Error on NYU-Depth V2 without retraining or architectural changes. Guided by Prof. Jitendra Malik, Anjoo Kanazawa. 

---

## Commercial / Mission-Facing Work

### Second Front Systems — Agentic Vulnerability Remediation
**TLDR:** Built an agentic system that turns vulnerability findings into concrete, auditable remediation actions for defense software.

Worked with Second Front Systems (DoD-accredited up to TOP SECRET) to build an agentic remediation engine that reasons over SBOMs, dependency graphs, and vulnerability metadata to propose actionable fixes (e.g., package upgrades, Dockerfile edits). Designed with compliance, reproducibility, and auditability as first-class constraints. Work was highlighted at a Second Front investor meeting.

---

### Falkonry — Adversarial Time-Series & State Inference (Electronic Warfare)
**TLDR:** Modeled adversarial EW signals where distribution shift is intentional and driven by an adaptive opponent.

Worked on ML systems embedded in Falkonry’s platform for electronic warfare and jamming contexts. Focused on latent state inference under adversarial, non-stationary dynamics with delayed or partial ground truth. The core challenge was separating structured behavior from deception, not anomaly detection.

---

## Technical Skills
Python, PyTorch, NumPy  
Distributed training concepts, mixed precision, experiment tracking  
Diffusion models, inference-time ensembling, sampling strategies  
Optimization dynamics and hyperparameter sensitivity  
Time-series modeling under non-IID and adversarial shift  
Agentic systems, graph-based reasoning, reproducible pipelines
