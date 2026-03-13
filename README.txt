---------------------------------------------------------------------------------

Written by Ankang Liu (email: liuankan@msu.edu), Michigan State University, 2025.

---------------------------------------------------------------------------------

Here, we present the supplemental code for our preprint "A Liu and M Dykman, Effect of hole-strain coupling on the eigenmodes of semiconductor-based nanomechanical systems, arXiv:2502.09769 (2025)".

"p-type_semiconductor_elasticity_code.zip" archive contains three Mathematica notebook files in it:
(1) "two-band_model_Si.nb" shows analytically how the energy dispersion laws for the light- and heavy-hole bands are expanded in power series of strain tensor. Then, it uses Mathematica built-in function "NIntegrate" to calculate the hole-induced corrections to the elasticity parameters in p-type silicon up to the fourth order. The code here simply utilizes the analytical expressions derived in our preprint and the silicon parameters from Winkler's book to perform the calculations. The correction to any component of the elastic constant in the two-band approximation can be calculated for a given hole density and temperature using this file.

(2) "two-band_model_GaAs.nb" is the same as "two-band_model_Si.nb" but uses the GaAs parameters given in Winkler's book to calculate the hole-induced corrections to the elasticity parameters for p-type GaAs.

(3) "three-band_model_Si.nb" gives the code that we have used to numerically evaluate the hole-induced corrections to the elasticity parameters in p-type silicon when the spin split-off hole band is taken into account. Details of the numerical method used here can be found in our preprint as well as the comments in the file. In this notebook, only certain combinations of the second- and fourth-order elastic constants, which are relevant to the MEMS modes we have studied in our preprint, are calculated.

You may need to install Mathematica in order to open and run the files. Please feel free to play with the code –– you may use it to reproduce our reported results in the preprint or modify it accordingly for your own purposes. Should you have any questions, please do not hesitate to contact us.

---------------------------------------------------------------------------------