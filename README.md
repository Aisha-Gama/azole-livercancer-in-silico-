# 🧬 In Silico Design, Docking, and ADMET Profiling of Novel Azole Derivatives as Potential Lung Cancer Therapeutics

## 🔍 Abstract
Lung cancer remains one of the most lethal malignancies worldwide, driving continuous efforts toward the development of more effective and selective therapeutic agents.  
This project focuses on the **computational design, molecular docking, and ADMET profiling** of **azole derivatives** as potential inhibitors of **VEGFR (PDB ID: 3U6J)** — a critical target in angiogenesis and tumor growth.  

The compounds were derived from the study by *Abdelhameid et al.* (“Design, Synthesis, and Cytotoxic Screening of Novel Azole Derivatives on Hepatocellular Carcinoma (HepG2 Cells)”) and are now being repurposed and computationally evaluated for lung cancer therapy.  
Docking simulations, ADMET predictions, and subsequent analyses aim to identify promising lead compounds for potential optimization and future experimental validation.

---

## 🎯 Objectives
1. To perform **molecular docking** of 27 azole derivatives and sorafenib against the VEGFR (3U6J) protein.  
2. To evaluate the **binding affinity** and **interaction profiles** of each compound.  
3. To carry out **ADMET and drug-likeness profiling** of top-performing ligands.  
4. To identify promising **lead compounds** for further optimization and synthesis toward lung cancer inhibition.  

---

## 📚 Source of Compounds
The azole derivatives used in this study were obtained from:

> **Abdelhameid, M.K., Zaki, I., Mohammed, M.R., & Mohamed, K.O.**  
> *Design, Synthesis, and Cytotoxic Screening of Novel Azole Derivatives on Hepatocellular Carcinoma (HepG2 Cells)*.  
> [Journal details — to be completed upon citation verification]

---

## 🧩 Methodology

### 1. Ligand Preparation
- **Design & Drawing:** Structures of 27 azole derivatives and sorafenib were drawn using **ChemDraw**.  
- **3D Conversion:** 2D structures were converted into 3D using **Chem3D**.  
- **Energy Minimization:** All ligands were optimized and exported as `.pdb` files.  
- **Cleaning & Optimization:** Ligands were cleaned and refined in **Discovery Studio** for docking readiness.

### 2. Protein Preparation
- **Protein Retrieval:** VEGFR (PDB ID: 3U6J) was downloaded from the **RCSB Protein Data Bank**.  
- **Cleaning:** Water molecules and non-essential chains were removed in **Discovery Studio**, hydrogens were added, and missing residues were corrected.

### 3. Molecular Docking
- **Docking Tool:** **PyRx (AutoDock Vina)** was used for docking simulations.  
- **Ligand and Receptor Loading:** Prepared ligands and VEGFR protein were imported into PyRx.  
- **Charge Assignment:** Gasteiger charges applied to both ligands and receptor.  
- **Grid Box Definition:** Coordinates centered on the VEGFR active site.  
- **Docking Execution:** Docking simulations were performed, and binding affinities (kcal/mol) were recorded.  
- **Visualization:** Complexes analyzed using **Discovery Studio Visualizer** to identify key interactions.

### 4. ADMET Profiling *(Planned/Next Stage)*
- **Tools:** SwissADME, pkCSM, and ADMETlab will be used for pharmacokinetic and toxicity prediction.  
- **Parameters:** Absorption, distribution, metabolism, excretion, and toxicity will be evaluated to identify drug-like properties.

---

## 🧰 Tools and Software
| Stage | Tool / Software | Purpose |
|--------|------------------|----------|
| Ligand Drawing | **ChemDraw** | 2D chemical structure design |
| 3D Conversion | **Chem3D** | 3D geometry building and energy minimization |
| Protein/Ligand Preparation | **Discovery Studio** | Cleaning, optimization, and visualization |
| Docking | **PyRx (AutoDock Vina)** | Docking simulation and scoring |
| Visualization | **Discovery Studio Visualizer** | Binding mode and interaction analysis |
| ADMET Prediction | **SwissADME**, **pkCSM**, **ADMETlab** | Pharmacokinetic and toxicity analysis |

---

## 🕒 Project Timeline
| Phase | Period | Description |
|-------|---------|-------------|
| **Initiation** | **July 2025** | Project idea conceived, literature reviewed, and workflow designed. |
| **Ligand Design** | July – August 2025 | Drew and prepared 27 azole derivatives (and sorafenib) using ChemDraw and Chem3D. |
| **Protein Preparation** | August 2025 | Retrieved and cleaned VEGFR (3U6J) protein structure from RCSB PDB using Discovery Studio. |
| **Molecular Docking** | September 2025 – Present (Ongoing) | Performing docking simulations with PyRx (AutoDock Vina) and analyzing results in Discovery Studio. |
| **ADMET Profiling** | Planned | Will perform pharmacokinetic and toxicity predictions using SwissADME, pkCSM, and ADMETlab. |
| **Lead Optimization** | Planned | Future phase for refining top-performing ligands to improve potency and selectivity. |

---

## 📊 Current Stage
✅ **Completed:** Ligand design, protein preparation, and molecular docking  
🧪 **In Progress:** ADMET profiling of top compounds  
⚗️ **Next Step:** Lead optimization and possible molecular dynamics (MD) simulation  

---


---

## 📈 Expected Outcomes
- Identification of azole derivatives with strong binding affinity to VEGFR.  
- Determination of compounds with favorable pharmacokinetic and safety profiles.  
- Selection of lead molecules suitable for optimization and potential synthesis.  

---

## 🧠 Future Work
1. Perform **ADMET and pharmacokinetic analyses** of top ligands.  
2. Apply **lead optimization** techniques to improve potency and selectivity.  
3. Conduct **molecular dynamics (MD) simulations** for stability validation.  
4. Explore **in vitro** testing to confirm computational predictions.

---

## 👩‍🔬 Author
**Aisha Umar Gama**  
B.Sc. Chemistry   
Independent Researcher in Computational Drug Design  
Supervised by **Dr. Mustapha Abdullahi**, Kaduna State University  

💬 *This work represents my independent initiative to learn and apply computational drug design techniques.  
Although I do not have formal postgraduate training yet, I am passionate about drug discovery and molecular modeling.  
With the kind guidance of Dr.Mustapha Abdullahi, I continue to develop my skills through self-learning, online courses, and hands-on research projects.*  

Department of Chemistry, Kaduna State University 
📧aisha.gama@kasu.edu.ng  

---

## 🧾 References
1. Abdelhameid, M.K., Zaki, I., Mohammed, M.R., & Mohamed, K.O.  
   *Design, Synthesis, and Cytotoxic Screening of Novel Azole Derivatives on Hepatocellular Carcinoma (HepG2 Cells)*.   

2. Trott, O., & Olson, A.J. (2010).  
   *AutoDock Vina: Improving the speed and accuracy of docking with a new scoring function, efficient optimization, and multithreading.*  
   *Journal of Computational Chemistry, 31*(2), 455–461.  

3. BIOVIA Discovery Studio Visualizer. Dassault Systèmes (2021).  
4. PyRx Virtual Screening Tool (2020). Available at: https://pyrx.sourceforge.io/  

---

## ⚗️ Keywords
*Azole derivatives, Sorafenib, VEGFR, Lung cancer, Molecular docking, ADMET, PyRx, Discovery Studio, In silico drug design*

