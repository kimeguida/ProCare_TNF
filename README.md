# ProCare: Unexpected binding site similarity between HIV-1 reverse transcriptase and tumor necrosis factor revealed by computer vision


[![Generic badge](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://shields.io/)  

Prospective application of ProCare to identify cavity similarities between remote proteins.  
Source data for:  
Eguida, M., Rognan, D. Unexpected similarity between HIV-1 reverse transcriptase and tumor necrosis factor binding sites revealed by computer vision.  
J Cheminform 13, 90 (2021). https://doi.org/10.1186/s13321-021-00567-3  

Contacts:  
Merveille Eguida, keguida(at)unistra[dot]fr  
Didier Rognan, rognan(at)unistra[dot]fr   


## Content
.
|-- input_data.tgz		---> ***prepared input structures  for binding sites and ligands comparisons***  
|-- binding_sites_comparisons		---> ***pockets similarity/distance scores***  
|-------- fuzcav_scores.tsv  
|-------- glosa_scores.tsv  
|-------- kripo_scores.tsv  
|-------- probis_scores.tsv  
|-------- procare_scores.tsv  
|-------- shaper_scores.tsv  
|-------- sitealign_scores.tsv  
|-- ligands_comparisons		---> ***ligands similarity scores***  
|-------- chembl_ligand_2d_similarity.tsv  
|-------- rocs.tsv  
|-------- tnf_hiv1rt_ligand_2D_similarity.tsv  
|-- amino_acids_standard.txt		---> ***standard amino acid list used by SiteAlign***  
|-- hiv1_rt_chembl_potent_inhibitors.tsv	---> ***ChEMBL HIV-1 RT ligands for 2D comparisons***   
|-- hiv1_rt_chembl_targets.txt  
|-- pdb_1vrt_query_results.txt		---> ***PDB query to retrieve HIV-1 RT structures + visual filtering***  
|-- pdb_1vrt_query_results_uniprot.txt		---> ***PDB query to retrieve HIV-1 RT structures + visual filtering***  
|-- pdb_1vrt_query.txt		---> ***PDB query to retrieve HIV-1 RT structures + visual filtering***  
|-- scpdb_hiv1_rt.tsv		---> ***final list of HIV-1 RT structures***  
`-- videoS1.mp4		---> ***ProCare-aligned HIV-1 RT cavity (purple point cloud) onto TNF-a cloud (white points) showing bound RT ligand (NVP)***  


## References
If you use these data, please cite the references below:  

- Eguida, M., Rognan, D. Unexpected similarity between HIV-1 reverse transcriptase and tumor necrosis factor binding sites revealed by computer vision.  J. Cheminf. 2021 13, 90.
- Eguida, M.; Rognan, D. A Computer Vision Approach to Align and Compare Protein Cavities: Application to Fragment-Based Drug Design. J. Med. Chem. 2020, 63, 7127–7142.
- Weill, N.; Rognan, D. Alignment-Free Ultra-High-Throughput Comparison of Druggable Protein-Ligand Binding Sites. J. Chem. Inf. Model. 2010, 50, 123–135.
- Lee, H. S.; Im, W. G-LoSA: An Efficient Computational Tool for Local Structure-Centric Biological Studies and Drug Design. Protein Sci. 2016, 25, 865–876.
- Wood, D. J.; Vlieg, J. De; Wagener, M.; Ritschel, T. Pharmacophore Fingerprint-Based Approach to Binding Site Subpocket Similarity and Its Application to Bioisostere Replacement. J. Chem. Inf. Model. 2012, 52, 2031–2043.
- Konc, J.; Janežič, D. ProBiS Algorithm for Detection of Structurally Similar Protein Binding Sites by Local Structural Alignment. Bioinformatics 2010, 26, 1160–1168.
- Schalon, C.; Surgand, J. S.; Kellenberger, E.; Rognan, D. A Simple and Fuzzy Method to Align and Compare Druggable Ligand-Binding Sites. Proteins Struct. Funct. Genet. 2008, 71, 1755–1778.
- Desaphy, J.; Bret, G.; Rognan, D.; Kellenberger, E. Sc-PDB: A 3D-Database of Ligandable Binding Sites—10 Years On. Nucleic Acids Res. 2014, 43, D399–D404.
- Bietz, S.; Urbaczek, S.; Schulz, B.; Rarey, M. Protoss: A Holistic Approach to Predict Tautomers and Protonation States in Protein-Ligand Complexes. J. Cheminform. 2014, 6, 12.
- OpenEye Toolkits 2020.2.0. OpenEye Scientific Software, Santa Fe, N. M., U.S.A., http://www. eyesopen. com (accessed Mar 30, 2021).
- RDKit: Open-source cheminformatics. http://www.rdkit.org (accessed Mar 30, 2021).
- Burley, S. K.; Bhikadiya, C.; Bi, C.; Bittrich, S.; Chen, L.; Crichlow, G. V.; Christie, C. H.; Dalenberg, K.; Di Costanzo, L.; Duarte, J. M.; Dutta, S.; Feng, Z.; Ganesan, S.; Goodsell, D. S.; Ghosh, S.; Green, R. K.; Guranović, V.; Guzenko, D.; Hudson, B. P.; Lawson, C. L.; Liang, Y.; Lowe, R.; Namkoong, H.; Peisach, E.; Persikova, I.; Randle, C.; Rose, A.; Rose, Y.; Sali, A.; Segura, J.; Sekharan, M.; Shao, C.; Tao, Y.-P.; Voigt, M.; Westbrook, J. D.; Young, J. Y.; Zardecki, C.; Zhuravleva, M. RCSB Protein Data Bank: Powerful New Tools for Exploring 3D Structures of Biological Macromolecules for Basic and Applied Research and Education in Fundamental Biology, Biomedicine, Biotechnology, Bioengineering and Energy Sciences. Nucleic Acids Res. 2021, 49, D437–D451.
- Gaulton, A.; Bellis, L. J.; Bento, A. P.; Chambers, J.; Davies, M.; Hersey, A.; Light, Y.; McGlinchey, S.; Michalovich, D.; Al-Lazikani, B.; Overington, J. P. ChEMBL: A Large-Scale Bioactivity Database for Drug Discovery. Nucleic Acids Res. 2012, 40, D1100–D1107.
