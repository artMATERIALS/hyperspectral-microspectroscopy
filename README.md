# MOSAIC-multiMOdal Spectromicroscopic data Analysis tool for Intelligent Correlation

### Workflow for analysis of hyperspectral datasets

<img src="https://github.com/artMATERIALS/hyperspectral-microspectroscopy/assets/151731956/a1223a62-beda-4fa0-b2c7-2a9e3cf57d02" width="500">

Workflow for analysis of hyperspectral datasets, in transmisison and electron yield mode.

Step 1: data are acquired in transmission and total electron yield mode

Step 2: data are preprocessed for drift correction and normalized

Step 3: images are reduced to a few components by performing a dimensionality reduction technique (ICA, PCA etc)

Step 4: clustering (k-means, GMM etc) is performed to these components to create the clustered transmission and electron yield image

### Glance into Li-ion battery

<img src="https://github.com/artMATERIALS/hyperspectral-microspectroscopy/assets/151731956/9f2ae7e2-e5d5-46b4-93c1-a901188bb551" width="500">

Scanning x-ray microscopy data for cycled Ti3C2 MXene with oxygen termiantions. Clustered image, acquired from transmission (electron yield) data at O K-edge, and corresponding transmission (electron yield) XA spectra. Areas of MXene (green), separator (yellow), and electrolyte residues (red) are shown. 

### Curve fitting of NEXAFS data

The curve fitting analysis involves background subtraction with a background function (arc tangent) to remove the excitation of core electrons to the continuum or quasi-continuum states. Peak fitting is performed with Gaussian functions. 

<img src="https://github.com/artMATERIALS/hyperspectral-microspectroscopy/assets/151731956/a53c329f-a57d-4a83-84b7-6a44dc61e150" width="500">

Fitted spectra at O K-edge for cycled MXene in LP30 electrolyte. OD spectra at O K-edge, for pristine MXene (blue), cycled MXene (green) with signs of Li-O bond (cyan peak) and carbonates interacted with MXene (red). 

#### References
Amargianou, F., Bärmann, P., Shao, H., Taberna, P.-L., SIMON, P., Gonzalez-Julian, J., Weigand, M., & Petit, T. (2024). Nanoscale surface and bulk electronic properties of Ti3C2Tx MXene unraveled by multimodal X-ray spectromicroscopy. https://doi.org/10.5281/ZENODO.10377233
