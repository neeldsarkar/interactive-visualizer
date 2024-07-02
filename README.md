# interactive-visualizer
Interactive Visualizer of Spatial Omics Website

The following HTML code is meant to set up an interface where a user uploads HDF5 files (.h5, .hdf5) and chooses either principal component analysis (PCA) or t-SNE as their dimensionality reduction method of choice. By uploading the file, client-side processing in the background will load the file into a readable dataframe that PyScript (a relatively new Python-HTML programming platform) can use to generate interactive figures.
