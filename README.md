# Ultra-NeRF_plus_plus
Code for ECCV Submission titled 'Ultra-NeRF++: Unlocking 3D Anatomical Reconstruction and View-Dependent Rendering in Ultrasound Imaging'

Code to train Ultra-NeRF++ for shape representations (volumetric as well as surface-based) on a single sweep is in file run main_mod1_2.py. 

Code to train Ultra-NeRF++ for view-dependence with multiple sweeps is in main_ vd_disjoint.py. Weights from training the network through main_mod1_2.py are used for initializing the network for view-dependence.

Warning: All paths to input and weight files need to be substituted for running the code. 
