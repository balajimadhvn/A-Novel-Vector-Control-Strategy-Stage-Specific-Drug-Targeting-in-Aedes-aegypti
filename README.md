# 🦟 A Novel Vector Control Strategy in *Aedes aegypti*

This project combines transcriptomics and computational drug discovery to develop a novel strategy for vector control of *Aedes aegypti*, the mosquito responsible for transmitting dengue, Zika, and chikungunya.

## 🔬 Project Overview

Using life-stage RNA-Seq data (embryo, larvae, pupae, adult), we identified stage-specific differentially expressed genes (DEGs) critical for mosquito survival.

### Key Steps:

- 🎯 **Target Discovery**: DEGs analyzed with DESeq2, GO/KEGG enrichment (g:Profiler, ClusterProfiler), and PPI network analysis (STRING, MCL).
- 🧬 **Protein Modeling**: Homology models built using Modeller and validated with MolProbity and AlphaFold comparisons.
- 💊 **Virtual Screening**: 1,073 ligands docked via AutoDock Vina, followed by ADMET filtering (SwissADME, ProTox-II).
- 🧪 **Ligand Optimization**: RDKit-based hybridization created 60 new drug-like molecules.
- 🔁 **MD Simulations**: GROMACS-based 100 ns simulations confirmed stability and binding efficiency.
- ✅ **Final Compound**: Exhibits strong binding, excellent ADMET profile, and low toxicity.

## 📁 Tools Used

- DESeq2, FastQC, Trimmomatic, STAR, Samtools, FeatureCounts  
- g:Profiler, ClusterProfiler, REVIGO  
- Modeller, PyMOL, TM-align, AlphaFold  
- AutoDock Vina, SwissADME, ADMETsar, ProTox-II  
- RDKit, GROMACS, MM-PBSA  

## 🧠 Skills Demonstrated

- RNA-Seq data analysis  
- Homology modeling & structural bioinformatics  
- Molecular docking & drug-likeness profiling  
- Molecular dynamics simulations  
- Computational drug design workflow development

## 📄 Publication-ready PDF

See [`manuscript.pdf`](./manuscript.pdf) for detailed methodology, figures, results, and references.

---

**🧑‍🔬 Author:** M.B.Balaji  
**📧 Contact:** balajimadhvn@gmail.com  
**🔗 Portfolio/LinkedIn:** www.linkedin.com/in/balajimadhvn




