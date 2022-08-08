# Prediction of drug-perturbed cancer cell line gene expression using graph neural networks

Author, primary contact: Nathaniel Evans, evansna@ohsu.edu  
Co-Authors: *Guanming Wu, Ph.D. , *Xubo Song, Ph.D.,  † Gordon Mills, Ph.D., M.D., *Shannon McWeeney, Ph.D.
  
*Division of Bioinformatics & Computational Biology, Department of  Medical Informatics & Clinical Epidemiology,  Oregon Health & Science University  
† Division of Developmental and Cancer Biology, Oregon Health & Science University   


Ineffective or limited precision oncology treatments are a cause of patient mortality. We seek to address this challenge by improving pre-clinical drug repurposing and drug combination discovery. We highlight the methodological challenge of training drug response models using single-drug data that will generalize well to multi-drug perturbations. We operate on the premise that protein-protein interactions mediate cellular drug response and hypothesize that incorporating this prior knowledge in a deep learning framework is liable to overcome limitations in drug response modeling. To do this we propose a machine learning model to predict drug-perturbed mRNA expression from intrinsic cancer features using graph neural networks (GNN) that operate on literature curated protein functional-interactions and drug-target interactions. We have shown promise of our approach using synthetic data and are in-progress of applying it to experimental datasets (LINCS L1000). The successful outcome of our method will enable novel GNN-based approaches to drug prioritization.  

Research reported in this poster was supported by National Center for Advancing Translational Sciences of the National Institutes of Health under award number TL1TR002371.  

# References 

1.	Wu, G. & Haw, R. Functional Interaction Network Construction and Analysis for Disease Discovery. in Protein Bioinformatics: From Protein Modifications and Networks to Proteomics (eds. Wu, C. H., Arighi, C. N. & Ross, K. E.) 235–253 (Springer, 2017). doi:10.1007/978-1-4939-6783-4_11.
2.	Subramanian, A. et al. A Next Generation Connectivity Map: L1000 Platform and the First 1,000,000 Profiles. Cell 171, 1437-1452.e17 (2017).
3.	LINCS Data Portal 2.0: next generation access point for perturbation-response signatures | Nucleic Acids Research | Oxford Academic. https://academic.oup.com/nar/article/48/D1/D431/5614562.
4.	Defining a Cancer Dependency Map: Cell. https://www.cell.com/cell/fulltext/S0092-8674(17)30651-7?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS0092867417306517%3Fshowall%3Dtrue.
5.	Barretina, J. et al. The Cancer Cell Line Encyclopedia enables predictive modelling of anticancer drug sensitivity. Nature 483, 603–607 (2012).
6.	Ghandi, M. et al. Next-generation characterization of the Cancer Cell Line Encyclopedia. Nature 569, 503–508 (2019).


