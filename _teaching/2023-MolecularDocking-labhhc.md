---
title: "Molecular Docking Colab"
collection: teaching
type: "Internal training"
permalink: /teaching/2023-MolecularDocking-labhhc
venue: "University of Medicine and Pharmacy at Ho Chi Minh city, Department of Organic Chemistry"
date: 2023-06-02
location: "City, Country"
---

This is a set of two (4) tutorials on basic information of molecular docking incoporating python framework, using the **Google Colab** free cloud-computing environment in **Summer 2023**. You can watch this [tutorial](https://www.youtube.com/watch?v=oCngVVBSsmA) to learn how to use **Google Colab**.
Please download the presentation [here](https://tieulongphan.github.io/files/docking_slide.pdf). Or you can read the [Vietnamse document](https://tieulongphan.github.io/files/docking_vn.pdf).

<a href="https://tieulongphan.github.io/files/docking_slide.pdf"><img src="/images/dock.png" target="_blank" alt="thesis slide" class="center" style="width:500px"></a>


## Introduction

These tutorials were created between May-June 2023 as part of the [**MedAI Training Session**](https://tieulongphan.github.io/teaching/) for full execution over Google Colab and remote accesibility via web browsers.
Each tutorial includes a brief introduction of the activities to be performed, installation instructions of the open-source software to be used in each session and several programming, visualization and data analysis activities to be achieved during the tutorial. 

After this training session, you will know:
- Install virtual environment con google colab with Miniconda
- Install fundamental packages for simple docking
- Get protein from RSCB and split ligand
- Visualization with py3dmol
- Add hydrogen and gasteiger to protein and ligand
- Conduct molecular docking using smina and quick vina 2
- Advance docking: blind docking, flexible docking and customize scoring functions
- Docking results analysis: indentify interaction and calculate RMSD (redocking)
- Retrospective control analysis (update...)

## Description of the Tutorials

The following is a brief description of each tutorial, along with the open-source software used for each task:

| Tutorial | Description                           | Software                                                        |
|--------|-------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------|
| Lab.01 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TieuLongPhan/TieuLongPhan.github.io/blob/master/_teaching/Material/Molecular%20Docking%20labhhc/lab01-theory_softwares.ipynb) | Theoretical concepts, Install software                         |    Miniconda, Obabel, py3dmol, RDKit, Autodock vina 1.2.0, vina-gpu, smina, qvina2, mgltools 1.5.7                                                                                                      |
| Lab.02 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TieuLongPhan/TieuLongPhan.github.io/blob/master/_teaching/Material/Molecular%20Docking%20labhhc/lab02-dock-pipeline-cpu.ipynb) | Molecular docking pipeline, redocking analysis, interactions extraction                         |    Miniconda, Obabel, py3dmol, RDKit, plip, Autodock vina 1.2.0, smina, qvina2, mgltools 1.5.7            |
| Lab.03 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TieuLongPhan/TieuLongPhan.github.io/blob/master/_teaching/Material/Molecular%20Docking%20labhhc/lab03-pdbfixer.ipynb) |  PDBfixer for missing residues handling                         |    Condacolab, openmm, pdbfixer, py3dmol, rdkit            |
| Lab.04 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TieuLongPhan/TieuLongPhan.github.io/blob/master/_teaching/Material/Molecular%20Docking%20labhhc/lab04-Advance_docking%20.ipynb) |  Advanced docking with smina: whole protein docking, flexible docking and reverse docking                         |    Miniconda, Obabel, py3dmol, RDKit, smina,  mgltools 1.5.7            |
| Homology [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sokrypton/ColabFold/blob/main/AlphaFold2.ipynb) |  Alphafold2                         |    Alphafold2            |


