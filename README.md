# Low-bias exciton quenching
This repository contains code for simulating photoluminescence quenching in organic light-emitting devices (OLEDs) operated at low biases. If you find this code useful, please cite our publication:

>J. S. Bangsund, J. R. Van Sambeek, N. M. Concannon, R. J. Holmes, Sub–turn-on exciton quenching due to molecular orientation and polarization in organic light-emitting devices. Sci. Adv. 6, eabb2659 (2020).

<img src="https://github.com/jsbangsund/low-bias-quenching/blob/master/Plots/teaser.png" alt="Photoluminescence quenching below device turn-on" width="600">

# Running this code
Most of the python code for the quenching simulations uses standard scientific python packages (numpy, matplotlib, scipy)--any python 3.5+ version of these packages should work. For an exact copy of the environment used in this publication, see the `oled.yml` environment file in https://github.com/jsbangsund/conda-envs. 

To edit the optical simulations of the optical generation profile and outcoupling efficiency, you will need `oledpy` (https://github.com/jsbangsund/oledpy) or your own preferred optical simulation package. Otherwise, the simulated optical profiles used in our publication are saved in the `Reference Data` folder.
