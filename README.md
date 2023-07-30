# Drug Design AutoDock Tools MBP/D-Ribose

Molecular Docking 

Molecular docking is one of the molecular modeling methods that predicts the preferred orientation of one molecule (ligand) to another (receptor) when bound to each other to form a stable complex (lowest energy state).

Apply a molecular docking on a ligand-receptor interaction.

The name of the receptor : 

Maltose-binding periplasmic protein (MBP) 

3pgf.pdb 

The structure of the receptor (screenshot) :

![1](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/f965ec96-db7e-4053-8417-bae5af7ccf91)

![2](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/625fffd2-3903-41fb-9573-44adad90b8e3)

![3](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/a86cf786-32ff-4adb-a0d3-e56a2137c080)

The functionality/type/aim of the receptor (Research, provide a reference) : 

Functionality: 

Maltose-binding protein (MBP) is a part of the maltose/maltodextrin system of Escherichia coli, which is responsible for the uptake and efficient catabolism of 
maltodextrins. It is a complex regulatory and transport system involving many proteins and protein complexes. 

Type: 

Maltose binding proteins (MBPs) are ubiquitous periplasmic binding proteins that serve as the primary receptors for alpha-linked glucose based oligosaccharides. While many bacteria have only a single copy of a more promiscuous MBP, some organisms contain more than one MBP isoform. 

Aim: 

Maltose Binding Protein Localization. The signal peptide of MBP serves two purposes. It slows the folding of the polypeptide and it helps it get to the membrane. 
Once the folding has taken place, the precursor can't enter in the translocation pathway. This causes a residue within the core to block the export. 

[https://www.nature.com/articles/nsmb.2002](Reference-1)

[https://pubmed.ncbi.nlm.nih.gov/21378967/](Reference-2)

[https://www.rcsb.org/structure/3PGF](Reference-3)

![4](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/7198c211-74d8-4d7f-8d7d-7ca106726e77)

![5](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/23b38802-dc84-4ef1-9f9d-6619663788da)

![6](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/71b6cc3d-1065-40e4-92a1-90c746edfd44)

How many chains the receptor has, if many, are they similar or different and how you will deal with them : 

3 Unique.  

Different from each other. 

A is our target as it works on Escherichia coli K-12 target organism. 

So, to be kept, but others B,C work on Homo sapiens not target organism in this project.

![7](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/15fb0613-8f32-4272-a6a8-38380983199a)

Does the receptor/protein need activators or inhibitors? 

Which one and What are they: 

No, it doesn’t.  

When obtaining the receptor was the format suitable for docking. If not, how you have dealt with it : 

Yes, it was found in a .pdb format, ready for docking. 

The name of the ligand : 

D-Ribose 

The structure of the ligand : 

![1](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/f6072679-555d-4baf-813d-c0c89658aca7)

![2](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/29db99c0-d23d-4372-a71e-d15ad06d52b5)

The functionality/aim of the ligand, how it affects the receptor (Research, provide a reference) : 

Functionality : 

Ribose (d-ribose) is a type of simple sugar, or carbohydrate, that our bodies make. It is an essential component of adenosine triphosphate (ATP), which supplies energy to our cells. 

Aim: 

D-ribose is a naturally occurring monosaccharide found in the cells and particularly in the mitochondria is essential in energy production. Without sufficient energy, cells cannot maintain integrity and function. Supplemental D-ribose has been shown to improve cellular processes when there is mitochondrial dysfunction. 
How it affects receptor: Ribose is a metabolite found in or produced by Escherichia coli (strain K12, MG1655). 

[https://pubchem.ncbi.nlm.nih.gov/taxonomy/511145](Reference-1)

[https://pubchem.ncbi.nlm.nih.gov/compound/10975657](Reference-2)

![3](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/ff027630-1223-4d6a-a47d-cbfd640e7b15)

When obtaining the ligand was the format suitable for docking. If not, how you have dealt with it:  

No, it was in SDF format , OpenBabel was used to covert it to PDB format.

![1](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/bc338fd5-5ad4-4104-bc4d-f0517ed1d6a3)

Some Information worth mentioning: 

Paper helped to get perfect protein/ligand pairs for docking :

[https://www.intechopen.com/chapters/43121](Paper-Link)

![1](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/c55156d7-5ce8-4426-9b66-ab1f8e5bd6d7)

Protein Author:

![1](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/b08872b8-3d13-4430-8aa8-1f375b252288)

X-Ray Crystallization done on protein experiment: 

![2](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/6f5e537a-d318-498c-8278-43ba289392d3)

SEQRES of 3pgf.pdb: 

![3](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/e07e826c-9fba-416b-af86-786e0b5abbd8)

Docking process of your chosen ligand and receptor:  

Mentioning the preparation needed for the receptor and the ligand : 

Receptor: 

1) Delete Water

![4](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/28fab8c4-ffdb-4a9c-bbba-089c0d557873)

2) Keep only active site A chain and remove others

![5](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/7b36a5e6-5ddd-4b6f-a94e-d36ba48c466d)

3) Delete Selected Atoms

![6](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/523ac3d1-fce5-4ba2-a7d7-86e97f612a09)

4)Add Polar Hydrogen Atoms 

![7](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/8b1fb147-0e4e-4417-baa0-72754a637bf2)

5) Add Kollman Charges

![1](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/e3cf5152-8a99-4eee-a052-98161722aa5e)

6) Assign AD4 Atoms Type 

![2](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/2c73c9b8-d99d-4612-8dba-550dda4b2e2c)

7) Save as PDBQT file extension

![3](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/dd8968cb-8f92-4d7e-961a-64ae887e4067)

Receptor:  

1) Input Ligand

![4](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/3ee7595d-6ef1-4448-b42a-78f0afc7ae35)

2) Detect Root:

![5](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/9d909acd-9ec0-4833-9786-f1dadcd6175c)

3) Save as PDBQT File:

![6](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/8ad6cd72-ce27-4a31-a43c-ef24eb8bef59)

Torsional Degrees of Freedom Of Ligand: 

![7](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/a5b8a9e2-606a-4cbe-8288-148ef126ad4f)

Apply blind docking on ligand and receptor.  

1)  Add Macromolecule to autogrid:

![1](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/b0964505-850f-4e41-beb9-367e3d323677)
  
2)  Add Ligand to autogrid:

![2](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/d38b4d38-e8e0-4172-acf0-fc62d4eda60a)

3)  Draw Grid Box:

![3](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/9462cdec-a4ab-4722-9240-aa21c1857a1b)

4)  Close Saving Current:

![4](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/21ce13e6-76c3-495c-a77a-176521a8b724)

5)  Save GPF File:

![5](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/51b2a005-e341-4bdd-a610-198075b3fa49)

6)  Run AutoGrid 4 :

![6](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/6be2e5f9-3ad6-4d0d-b46f-246d144e3b4b)

7)  Add MacroMolecule to autodock:

![7](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/3d72c3ad-efa3-40b2-a827-54226d8ae40a)

8)  Add Ligand to autodock:

![8](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/a43e6577-88b9-4e2d-b844-0b91930a3f5b)

9)  Accept Ligand Parameters:

![9](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/406fa7b7-3491-4abd-b1d9-dea8a91d3349)

10)  Set Search Parameters to Genetic Algorithms: 

![10](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/cc24f777-9a88-473b-91b0-cfdf9621c34f)

11)  Save Docking Output to Lamarckian:

![11](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/31044cf8-3dae-4f55-a0b7-5053d4426720)

12)  Run AutoDock:

![12](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/33ead1a6-5f26-4d89-b5de-3ea761d72222)

![13](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/8011041d-954d-4c40-b78f-25ffd270a6fa)

Show your analysis and comment on the your findings. Which docking you have applied? (flexible or rigid) docking.  

This is Rigid Docking as receptor/protein was fixed , we only treated ligand as flexible and changed its configuration.  

Analysis: 

1) Delete all molecules :

![14](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/06e7e4bf-e371-4ca3-8e30-4fb45df0d4df)

2) Analyze DLG file: 

![15](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/6e61bd1b-3fa1-4b3c-9457-a58436cabccc)

3) Analyze Macromolecule Open:  

![16](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/692d9b3d-9871-4759-8c5d-fa8c29c9ad58)

4) Analyze Info: 

![17](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/e06caaf5-3243-47ed-b878-2ffc1a205938)

5) Best Binding Energy Run no 4 According to RMSD Table Analysis in AutoDock -4.03 : 

![18](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/0cc08cc6-00fe-4bcd-878e-3787e64d5f84)

6) RMSD Table of DLG File Run 4 wins: 

![1](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/238d9508-a05f-4460-85be-0cef418c5a17)

7) Run 4 Details

![2](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/8528cab9-bbec-4df6-b9a3-83e82e467c9e)

8) Final Directory Files: 

![3](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/66f14695-fd02-44fc-9449-38be60886692)

Apply Site-specific Docking

Instead of applying blind docking on the selected receptor and ligand molecules, perform a research to discover the active binding site of the target 
receptor, and apply the auto-grid and auto-dock on the active site only.  

Reference on active binding sites in MBP protein:

[https://www.nature.com/articles/nsmb.2002](Reference)

![4](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/a43d95bc-a8e1-41d5-ab94-2267ee649c3f)

1) Select Active Sites in Protein: 

![5](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/3a34f037-78bb-4313-acee-2809ef25a140)

2) Draw Grid Box Only around these active site: 

![6](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/8b74ae36-ea62-4250-b50f-2615b43fedb8)

3) Run AutoGrid: 

![7](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/7f9ad91c-e29c-4286-b355-c0d01436357a)

4) From Analysis to find run 7 of rank 1 of least binding affinity energy -4.71 : 

![8](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/b53a58f3-0706-4646-802f-053b9845302d)

5) RMSD Table : 

![1](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/57c330e7-670b-487c-a3da-dd82e40b7d43)

6) Run 7 Details:

![2](https://github.com/Sarah-Hesham-2022/Drug-Design-AutoDock-Tools-MBP-D-Ribose/assets/112272836/f34c2f55-9e23-4cfe-abf0-2523ad62d2d9)


Final note : 

Binding Affinity Energy changed from -4.03 in blind docking best rank was run no 4 to -4.71 in active site docking best rank run was no 7. 

References :  

-Here’s the paper we used a reference to select our protein and ligand, It shows some pairs of protein and its suitable ligand and pdf in files as well: 

-Protein PDB: 

-Protein Journal: 

-Protein Journal on PubMed: 

-Ligand from PubChem: 

-Reference on active binding sites in MBP protein: 

-We used the AutoDock documentation file that’s attached in the submitted files to solve some errors we faced while working:


