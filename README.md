# Jingjing Yan, Ph.D.

**Preclinical Scientist × AI/ML Researcher — Building at the intersection of drug discovery and machine learning**

I bring 8+ years of hands-on oligonucleotide/siRNA drug development (AstraZeneca, Glaukos, Biogen, Eli Lilly/Prevail) together with graduate-level ML research (Georgia Tech MS in CS/ML). My work sits at a unique intersection: I've advanced real drug candidates through the preclinical pipeline *and* built ML systems that improve how we predict molecular properties and understand model behavior.

I'm actively exploring roles in **AI-driven drug discovery** — the kind of work happening at Isomorphic Labs, Recursion, Relay Therapeutics, and within AI/ML groups at Lilly, AstraZeneca, Novartis, and Roche.

---

## What I'm Working On

### AI for Drug Discovery — ADMET Prediction
Applying graph neural networks and gradient-boosted models to predict molecular ADMET properties using the Therapeutics Data Commons benchmark suite.

**[TDC-ADMET-Pgp-AttrMasking](https://github.com/jingjingyan1/TDC-ADMET-Pgp-AttrMasking)** — Pretrained GIN with attribute masking for P-glycoprotein substrate prediction. Achieved **AUROC 0.937 ± 0.004**, ranking #2 on the TDC leaderboard. Includes XGBoost + Morgan fingerprint baseline (AUROC 0.912). Preprint submitted.

*Upcoming: expanding to additional ADMET endpoints (Caco-2, BBB, hERG, CYP450s) and exploring multi-task learning across the full 22-dataset ADMET benchmark.*

### LLM Alignment & Mechanistic Interpretability
**[SycoSteer](https://github.com/jingjingyan1/SycoSteer)** — A causally-validated activation steering framework that reduces sycophantic behavior in large language models. Applied contrastive activation addition (CAA) across Mistral-7B's transformer layers, achieving a 63% reduction in sycophancy on TruthfulQA with zero degradation on reasoning benchmarks (ARC, MMLU). Includes full-layer sweep analysis, cross-model comparison (5 models), and causal validation via activation patching.

---

## Why This Combination Matters

Most people in AI-for-pharma come from one side: either computational (ML/CS background, learning biology) or experimental (bench scientists picking up Python). I've spent years on both sides.

**On the bench:** Led bioanalytical strategy for GalNAc-siRNA and ASO programs at AstraZeneca. Developed LC-MS/MS methods for conjugated siRNA quantification. Ran PK/biodistribution studies across liver, kidney, heart, lung. Made candidate drug investment decisions based on ADMET data I generated.

**On the compute side:** Built GNN models that predict the same molecular properties I used to measure experimentally. Designed interpretability frameworks for transformer models. Understand both *what* ADMET data means for a drug program *and* how to build models that predict it.

This means I can ask the right biological questions when building ML models, and I can evaluate ML predictions with the skepticism of someone who has generated ground-truth data.

---

## Technical Stack

**Drug Discovery & Cheminformatics:** RDKit, Morgan fingerprints, molecular descriptors, SMILES, PyTDC, DeepPurpose, DGL/DGLLife, XGBoost, molecular property prediction

**Deep Learning & ML:** PyTorch, PyTorch Geometric, GNN (GIN, GCN, AttentiveFP), transformer architectures, contrastive activation addition, activation patching, Hugging Face

**Preclinical & DMPK:** LC-MS/MS bioanalysis, PK/PD modeling (Phoenix WinNonlin), GalNAc-siRNA/ASO platforms, metabolite ID, tissue biodistribution, SPE method development

**Languages & Tools:** Python, SQL, Git, Docker, Google Colab, Runpod (cloud GPU)

---

## Selected Publications

- Lovrić, J.; **Yan, J.**; Li, X.-Q.; et al. In vitro Structure-Activity Relationship Stability Study of ASO Therapeutics. *Pharmacology Research & Perspectives*, 2025.
- Bhattacharya, C.; **Yan, J.**; et al. Application of AMS to Characterize Mass Balance Recovery and Disposition of AZD4831. *Drug Metabolism & Disposition*, 2023.
- **Yan, J.**; MacDonald, J.; Burdette, S. MOF Decomposition Using a Photodegradable Strut. *Chemistry – A European Journal*, 2019.
- **Yan, J.**; et al. Detection of Adsorbates on Emissive MOF Surfaces with XPS. *Dalton Transactions*, 2019.

---

## Education

- **Ph.D. Chemistry & Biochemistry** — Worcester Polytechnic Institute
- **B.S. & M.S. Chemistry** — Nankai University

---

## Contact

- Email: jingjingyan1@gmail.com
- LinkedIn: [linkedin.com/in/jingjing-yan-46868258](https://linkedin.com/in/jingjing-yan-46868258)
- ORCID: [0009-0008-3364-4394](https://orcid.org/0009-0008-3364-4394)
