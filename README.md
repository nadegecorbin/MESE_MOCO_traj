# MESE_MOCO_traj

The code generates the trajectory of the k-space sampling 
of the 3D radial multi-echo spin-echo sequence
with motion correction and acceleration capabilities
proposed in the manuscript: <em>Whole-brain T2 mapping with radial sampling and retrospective motion correction at 3T</em>
submitted in the Magnetic Resonance in Medicine journal in October 2023. 

The user can define set of parameters and visualize the resulting trajectory of any "intermediate image" or " image" as defined in the paper.

The easiest way to run the code is to use Google Colab by clicking on the icon. 

Note that this code is not optimized
for the python language but rather matches the C++ implementation 
required for the Siemens MR pulse sequence. 
The only difference with the C++ implementation is the "random.shuffle" fonction 
which is completely coded in C++ from scratch for the MR pulse sequence

