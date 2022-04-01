# Beam-Loss-Monitor
The user needs to install lcls-live conda environment to have access to pytao.

Setup Instructions

(1) Create lcls-live environment ( which includes conda-forged version of Bamd and Tao )

(a) Copy https://github.com/ChristopherMayes/lcls-live/blob/master/environment.yml

(b) conda env create -f environment.yml

(c) source activate lcls-live

(d) python -m ipykernel install --user --name lcls-live --display-name Lcls-live


(2) Gain access to lcls-lattice

If on personal computer, git clone https://github.com/slaclab/lcls-lattice.git

If on SLAC SDF, use Chris’s directory: export LCLS_LATTICE=/u/ad/cmayes/nfs/GitHub/lcls-lattice/

For details go to https://slaclab.github.io/lcls-live/getting-started.html
