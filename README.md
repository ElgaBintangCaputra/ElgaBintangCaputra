# Hi, I'm Elga Bintang Caputra 👋

### Computational Biology & Bioinformatics Portfolio

I started with a deep curiosity for **Biology**, then pursued **Software Engineering (*Rekayasa Perangkat Lunak / RPL*)** to learn how to build systems through code. Along the way, I realized I didn't have to choose one over the other—by combining software engineering, statistics, and machine learning with biological data, I found my passion in **Computational Biology and Bioinformatics**.

To explore how computation can solve real biological and conservation problems in Indonesia, I have built several end-to-end research projects spanning clinical transcriptomics, molecular phylogenetics, network pharmacology & cheminformatics, and stochastic conservation modeling.

---

## 🔬 Featured Research Repositories *(Click any project to open its full repository)*

| Project | Domain & Methods | Key Verified Outcomes | Repository |
|---|---|---|---|
| **🫁 TB-Signature** | Host Blood Transcriptomics (`GSE19491` → `GSE37250`), Welch + BH-FDR, Nested 5×4-Fold CV Anti-Leakage ML, Strict LODO, Single-Sample Calibration, *Sweeney 3-Gene* Benchmark, Boolean Network & ODE | 967 DEGs (`FDR < 0.05`); 8-gene signature Nested CV `AUC = 0.927`, External `AUC = 0.922` (*Active vs Latent TB*, $n=537$, Single-Sample `AUC = 0.910`); Strict LODO South Africa `AUC = 0.957` | [Open TB-Signature ↗](https://github.com/ElgaBintangCaputra/TB-Signature) |
| **🐟 NusantaraBarcode** | COI DNA Barcoding (29 Indonesian commercial fish species), MAFFT, IQ-TREE 2 (`GTR+F+I+G4`), K2P, Vertebrate Mitochondrial ORF Verification, Asymmetric GenBank Audit, 6-mer ML Ablation, Snakemake | 23× inter/intraspecific K2P gap; 0 internal stop codons (212 codons); 97.2% 3rd-codon polymorphism; 6-mer RF accuracy `97.38%` → `98.68%` (post-audit) → `99.56%` (*Thunnus* complex resolved) | [Open NusantaraBarcode ↗](https://github.com/ElgaBintangCaputra/NusantaraBarcode) |
| **🌿 JamuNet** | Network Pharmacology (6 Indonesian herbs × T2D), RDKit, ChEMBL, Open Targets, STRING PPI, MedChem Lead Score, Scaffold-Split & GroupCV5 QSAR (`DPP4`), PAINS vs Brenk, 10-Conformer 3D `.sdf` | 47 overlapping T2D targets (`DPP4`, `PPARA`, `GSK3B`, `PTGS2`); `naringenin` & `kaempferol` top clean leads (`PAINS=0, Brenk=0`); DPP4 QSAR Scaffold-Split `AUC = 0.924` + Applicability Domain | [Open JamuNet ↗](https://github.com/ElgaBintangCaputra/JamuNet) |
| **🦏 NusantaraRhino** | Integrated 3-Engine Javan Rhino PVA (IBM + 20-Loci IBD Genetics + Gaussian Copula Catastrophes), 5 Factorial Scenarios (A–D), Latin Hypercube Sampling & True PRCC, 95% Wilson CI, Vortex 10 Spec Bridge | Baseline quasi-extinction `54.0%` vs Managed UKNP `0.8%` vs Integrated Strategy D `0.0%` extinction (`Mean N100 = 107.1`, `95.5%` $H_e$ retained); adult survival top driver (`PRCC = -0.847, p < 0.0001`); IMRaD manuscript | [Open NusantaraRhino ↗](https://github.com/ElgaBintangCaputra/NusantaraRhino) |

---

## 🌐 Research Portal Index

Want a single guided overview linking all four domains? Visit **[Computational Biology and Bioinformatics](https://github.com/ElgaBintangCaputra/Computational-Biology-and-Bioinformatics)**.

---

## 🛠️ Core Computational Stack

`Python` • `NumPy` • `Pandas` • `SciPy` • `scikit-learn` • `Biopython` • `RDKit` • `NetworkX` • `Pydantic` • `Snakemake` • `MAFFT` • `IQ-TREE 2` • `Plotly` • `Streamlit`
