# DC-SVDM - Multi-Tensor Multi-Conformation SVD Fit in DC program

The package includes a binary executable (DC++) for running the DC function of the Multi-Tensor Multi-Conformation SVD Fit. To view the available arguments and options, use the command:

DC++ -help

Below is an example command line demonstrating how to run the Multi-Tensor Multi-Conformation SVD Fit using two example files for the apo-MBP protein:

./DC++ -inD inD_apo_res3.tab -pdb apoMBP_1OMP_ens2.pdb -multiTensor

The provided binary is intended for Linux systems with a standard GNU C++ library installed. Versions compatible with other operating systems (macOS and Windows) will be made available soon. Source code is also available upon request.

For added convenience, a web-based server is available to run the Multi-Tensor Multi-Conformation SVD Fit. You can access it at:
https://spin.niddk.nih.gov/bax-apps/nmrserver/dc/svdm.html
