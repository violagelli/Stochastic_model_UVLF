# Stochastic_model_UVLF

Gelli, Mason & Hayward 2024 (https://ui.adsabs.harvard.edu/abs/2024arXiv240513108G/abstract)

`LF/` contains the UV luminosity functions for the mass-dependent UV scatter model. The two columns are:
- UV magnitude Muv [mag]
- number density log10_phi [/mag/Mpc^3]

`SFRD/` contains the redshift evolution of the UV luminosity density (obtained by integrating the UVLF down to Muv=-17) and the star formation rate density (derived using [Madau+99](https://iopscience.iop.org/article/10.1086/306975)). The columns are:
- redshift z
- luminosity density log10_rhoUV [erg/s/Hz/Mpc^3]
- star formation rate density [Msun/yr/Mpc^3]