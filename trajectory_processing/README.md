# Processing of raw trajectory data

trajectory_analysis.ipynb: Main conformational analysis of channel with and without $V_\mathrm{TM}$, for the WT and te L80K/D and S1rrR/D mutants. Contains pore diameter analysis, conformational analysis and calculation of residue-wise distance from the channel pore.

process_pfr_files.ipynb: Processing of .pfr files written out by gromacs-fda to obtain arrays of (vector-valued) pairwise forces.

backbone_only_field.ipynb: Calculation of residue-wise distance from the channel pore for simulations with "backbone-only" electric field

FDA_analyze_change_in_pairwise_forces.ipynb: Creation of tables listing pairs of residues that experience the strongest change in pairwise force upon application of $V_\mathrm{TM}$. Creation of .dat files for visualization of changes in pairwise forces $\Delta \mathbf{F}_{ij}$ in VMD networkview.