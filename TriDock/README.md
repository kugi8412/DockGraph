# 🧬 Computational Biology Project – Identification of Inhibitors of SLC6A20 (SIT1)

## 🎯 Course Overview

The website for this year's edition can be found here: https://meet-eu-25-26.github.io/.

You can watch the [video of the kickoff](https://eu02web.zoom-x.de/rec/share/GbFriRgpE9oL_AyGNT7eqARbQi36wIq89b6aQXG6P_JyiWdsSA8nP0OqK4gk9xT5.ixmTO7yVZnKXi1qO) with the Passcode: 6t*fZ8ve.

You can download the [video of the mid-term meeting](https://filesender.renater.fr/?s=download&token=968a2c8f-964f-408b-be9f-dd35aae4a420). 

Please register yourself in this sheet: https://docs.google.com/spreadsheets/d/1hLPbAlXz9OV46WXwTCf1yboJP5rk3Hafsf8hVgEwWuo/edit?usp=sharing.

We focus on the identification of putative inhibitors for a **Solute Carrier Transporter (SLC) target**. The specific aim is to identify a pocket, putative inhibitors and the molecular determinants of the recognition specificity. 

The subject detailed description can be found [here](https://github.com/meet-eu-25-26/shared-material/blob/main/Docs/Meet-EU%20SLC%20subject.pdf).

<p align="center">
  <a href="https://github.com/user-attachments/assets/56bca77f-cc1e-4ded-8776-ebc6594b7571" target="_blank">
    <img alt="Figure_Trends"
         src="https://github.com/user-attachments/assets/56bca77f-cc1e-4ded-8776-ebc6594b7571"
         width="600" />
  </a>
</p>


In this repository, you can find material to help you,
- Biblio: key reference papers
- Codes: notebooks and helper scripts
- Data: tables, pymol sessions, etc. with information about the target and the compounds
- Docs: documents, including the detailed description of the subject.


## 🧬 SLC6A20 (SIT1) – Key Information

| Conformation | Ligand | PDB | Description |
|--------------|---------|-----|------------|
| Occluded | Proline (substrate) | 8I91 | SLC6A20 bound to its natural substrate |
| Inward-Open | Tiagabine (inhibitor) | 8WM3 | SLC6A20 bound to a known inhibitor |
| Outward-Open | Model | SIT1_Model_OO | Homology model based on SLC6A19 |

---

## 🧪 Course Objectives

Design and implement a **pipeline** that:

1. Analyzes the **sequence and/or structure** of SLC6A20 and homologs.  
2. Identifies and characterizes **binding sites** (orthosteric and/or allosteric).  
3. Evaluates **residue specificity** among SLC6 homologs.  
4. Screens a set of **small molecules** to identify potential inhibitors.  
5. Produces a **ranked list of inhibitors** based on interaction and specificity scores.  

> The entire process must be **automated, reproducible, and well-documented**.

## 📋 Deliverables

Each group must provide:

1. 🧾 **Fully automated program or pipeline**  
   - Accepts example inputs and produces results without manual intervention  

2. 📈 **Clear documentation**
   - Instructions for installation and execution  
   - Description of inputs, outputs, and pipeline logic  

3. 📊 **Results**
   - List of binding site residues with specificity scores  
   - Ranked top 10 predicted inhibitors  
   - Optional: confidence or interaction scores  

4. 💬 **Report or presentation**
   - Explaining scientific rationale, methodology, and results  

---

## 🧪 Optional Auxiliary Tasks

### 1. Small Molecule Dataset
- Retrieve analogs from **ChemBL**  
- Repurpose ligands from **DrugBank**  
- Apply **Deep Docking (DD_protocol)** for large-scale screening  

### 2. Conformational Sampling
- Use the **outward-open homology model**  
- Generate alternative conformations with **BioEmu**  
- Consider different **isoforms of SLC6A20 (V1 and V2)**

---

## 🎓 Expected Outcomes / Learning Goals

By completing this course, students will be able to:
- Integrate **biological and computational reasoning**  
- Manipulate **sequence and structure data**  
- Build **reproducible computational pipelines**  
- Apply **molecular docking or deep learning approaches**  
- Interpret and communicate complex bioinformatics results  

---

## 🧭 Suggested Workflow

```text
1. Understand the target and gather structural data
2. Define binding pockets and specificity
3. Build or retrieve compound datasets
4. Implement and automate the pipeline
5. Test, validate, and document
6. Present results
