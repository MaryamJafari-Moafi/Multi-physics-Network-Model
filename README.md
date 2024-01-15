# About Multi-physics Network Model (MpNM)
MpNM is a network model framework for simulating multi-physics processes (e.g. flow and heat) in porous media written in Python, which is developed by Zhejiang University and Imperial College London. In addition to standard network model using a single pore network (e.g. generated by pnextract developed by Imperial College London), MpNM can link two networks (e.g. pore network and solid network dual-network model) to simulated coupled mass and heat transfer in both pore space and solid phase. This model is compatible with the pore network extraction algorithm developed by Imperial College London (https://github.com/ImperialCollegeLondon/pnextract). The source code is being prepared into different modules and will be uploaded continuously with the example datasets for demonstration.

## Example 1 Absolute permeability (Being upload)

Folder ```sample_data/Bead_packing``` is the example computing absolute permeability. There are four required input network files (*_link1.dat, *_link2.dat, *_node1.dat, *_node2.dat). These files can be generated using pnextract (https://github.com/ImperialCollegeLondon/pnextract).

* Locate the folder ```single_phase_flow```
```
python single_phase_permeability.py 
```
## Example 2 Coupled heat and mass transfer
This example is to simulate heat and mass transfer using a dual-network. 

# Contact
Please contact us if you need more demos or information:

Qingyang Lin - qingyan_lin@zju.edu.cn
Mingliang Qu - mingliangqu@zju.edu.cn
