# DC-SVDM - Multi-Tensor Multi-Conformation SVD Fit in DC program
Contains a binary file (DC++) for running the DC function of multi-tensor multi-conformation SVD fit, type "DC++ -help" to see all allowed arguments and options. 

To run the Multi-Tensor Multi-Conformation SVD Fit, an example command line with two attached example files for the apo-MBP protein is listed below:

./DC++ -inD inD_apo_res3.tab -pdb apoMBP_1OMP_ens2.pdb -multiTensor


Note that the binary DC++ is only for a Linux OS with a standard GNU C++ library installed. The binary for other OS (Max and Windows) will be provided soon, the source codes are also available upon request.
A convienient web-server is alo provided to run the Multi-Tensor Multi-Conformation SVD Fit, and can be accessed at https://spin.niddk.nih.gov/bax-apps/nmrserver/dc/svdm.html 
