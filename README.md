This repo contains starter code and data for the paper 'Automated knowledge extraction from polymer literature using Natural Language Processing'. The Word2Vec model described in the paper can be found at 10.6084/m9.figshare.13211015 .

A detailed description of the files is given below:

notebooks/Model\_evaluation_demo.ipynb - starter code to access the word vector model and compute analogies with it

data/Mat-intelligence_data/apl.json - A list of application tokens for the materials science space. More info on this can be found in [1](https://pubs.acs.org/doi/abs/10.1021/acs.jcim.9b00470)

data/analogies\_dataset/modified_analogies.txt - Contains analogy pairs for general english language and inorganic materials science tasks. More info on this can be found at

data/analogies\_dataset/analogy\_plot_entries.csv - Contains the analogies used to plot Fig. 5 in the paper

data/polymer_datasets - contains the analogy pairs for each task in Table 1 of the paper

##References

[1] Weston, Leigh, et al. "Named entity recognition and normalization applied to large-scale information extraction from the materials science literature." Journal of chemical information and modeling 59.9 (2019): 3692-3702.
