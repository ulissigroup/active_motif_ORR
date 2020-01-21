# active_motif_ORR
- Active motif based screening to discover active, selective and stable ORR catalysts for H2O2 production

# active_motif_notebook
- There are series of notebooks used to collect data from Materials Project, to evaluate electrochemical stabilities, to enumerate surfaces and sites, to find isolated sites, and finally save docs and trajectories files.

# docs_Uranium_attached
- Using the notebooks, I generated "docs" containing surface information such as miller index, mpid and shift values. Uranium atom has been added at the top site of isolated sites. 
- These structures can be used to generate O* adsorbed (by replacing U with O), OOH* adosrbed surfaces (by replacing U with O and add OH on that O), or bare surfaces (by removing U). More details can be found in "04_isolated_sites.ipynb".

# o_ooh_trajectories
- Genreated trajectories of O* and OOH* adsorbed surfaces using "04_isolated_sites.ipynb". 
- All calcualtions are being performed in Arjuna (last update: Jan 21 th, 2020)
- Seoin will analyze and upload DFT data once completed. 
