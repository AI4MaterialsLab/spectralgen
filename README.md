# spectralgen

This repository contains the code and data supporting the work: "Generative adversarial networks for data-scarce radiative heat transfer applications” by Juan José García-Esteban, Juan Carlos Cuevas y Jorge Bravo-Abad, submitted for publication (2023).

## Files included in the repository

- spectralgen_code.ipynb: Main file of the repository, contains all the relevant code related to the work mentioned above. Code is ready to be executed, but some parts require of the other files in the repository.

- labels8metal.csv: Data file containing the physical sizes of the data examples. In this context, they correspond to the labels of the dataset.

- data8metal.cosv: Data file containing the HTC spectra of the data examples. In this context, corresponds to the training target. Biggest file in the repository.

- GAN_8metal_020_CGAN.h5: Pre-trained CGAN generator used to create some figures. Corresponds to a data split of 80% training and 20% validation.

- GAN_8metal_020_v3g.h5: Pre-trained CWGAN generator used to create some figures. Corresponds to a data split of 80% training and 20% validation.
