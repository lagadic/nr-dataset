# NonRigidDataset

This dataset contains two simulated data:

1) Board

2) Cube


The image and depth files are provided in the respective folders. The object models at the initial, undeformed condition are also provided (in .obj format).



------------------------

The camera parameters are as follows:


C_x  320.0

C_y  240.0

F_x  700.0

F_y  700.0

The depth and color camera are the same, unlike real depth sensors. Therefore, no transformation between camera and depth sensor.


------------------------

The ground-truth for the deformation are provided in a .tar file inside the respective folders.

------------------------


This dataset (in the 'master' branch) has been utilized in the paper: 


**Agniva Sengupta, Alexandre Krupa, Eric Marchand. Tracking of Non-Rigid Objects using RGB-D Camera. SMC 2019 - IEEE International Conference on Systems, Man, and Cybernetics, Oct 2019, Bari, Italy.**

	@inproceedings{sengupta:hal-02178353,
	TITLE = {{Tracking of Non-Rigid Objects using RGB-D Camera}},
	AUTHOR = {Sengupta, Agniva and Krupa, Alexandre and Marchand, Eric},
	URL = {https://hal.inria.fr/hal-02178353},
	BOOKTITLE = {{SMC 2019 - IEEE International Conference on Systems, Man, and Cybernetics}},
	ADDRESS = {Bari, Italy},
	PUBLISHER = {{IEEE}},
	YEAR = {2019},
	MONTH = Oct,
	PDF = {https://hal.inria.fr/hal-02178353/file/2019_sengupta_smc.pdf},
	HAL_ID = {hal-02178353},
	HAL_VERSION = {v1},
	}
