# Inference of Attentional Mechanisms in Cognitive Tasks
**sEEG analysis across Rest · Music · Speech**

Analysis notebooks from my internship at the **Theoretical Neurosciences Group (INS)**, supervised by **Dr. Marmaduke** and **Dr. Meysam**.  

---

## What each notebook does
- **Introduction_to_Bayesian_Inference.ipynb** – Short tutorial notebook connecting SBI choices to the later analyses.
- **Refactored_BVEP_SBI.ipynb** – Simulation-based inference on the 2D **Epileptor** for the paramaeter η refactored. 
- **Tau_BVEP_SBI.ipynb** – Simulation-based inference on the 2D **Epileptor** for the time constant parameter τ. 
- **TNG_Z_BVEP.ipynb** – Prototype amortized estimator for streaming **slow-state \(z\)** (assumes τ known/tightly constrained).

- **sEEG_Analysis.ipynb / seeg_Desc.ipynb** – Exploratory loading, PSDs, metadata checks, channel counts, simple figures.


- **dimReduce.ipynb** – PC1–PC2 geometry per condition; silhouette-selected **k-means** clusters; **HMM** state assignments, transition matrices, dwell times, and a pooled off-diagonal “transition propensity.”
- **timescaleSys.ipynb** – **specparam** decomposition (aperiodic + peaks) and **autocorrelation-based τ** with bootstrap CIs; subject/condition summaries.
- **ldsAnalyze.ipynb** – Stable **LDS** fits (2D latent); eigen-derived **τ₁, τ₂** and **LAS = log₂(τ₁/τ₂)**; latent vector fields and short-horizon rollouts; exports per-channel τ/LAS for mapping.
- **rSLDS.ipynb** – **Recurrent SLDS**: state transitions conditioned on latent position; regime occupancy/dwell, decision surfaces, per-state vector fields.
- **causalDrivers.ipynb** – **Recurrence analysis**: ETD/AMI embeddings → low-rank variance score & forced-response dispersion; ranks putative **driver** channels per condition.
- **electrodeMapping.ipynb** – Contact → **Destrieux** parcel (probabilistic) mapping; parcel-wise aggregates of **LAS, τ, driver strength/density**; condition contrasts; cross-method correlations (e.g., LAS vs. causal driver strength).


---

## Data access 

 **No data are included in this repository.**  
 The hospital sEEG recordings are **restricted** and governed by INS/institutional agreements.  

##  License
Copyright (c) INS. All Rights Reserved.

This repository and its contents are proprietary and confidential.
Unauthorized copying, redistribution, modification, or use of any
files in this repository, via any medium, is strictly prohibited
without explicit written permission from INS.
