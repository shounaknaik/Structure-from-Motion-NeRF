Phase 1


1) To run the Structure from Motion script:

Run `python3 Wrapper.py` in the `./Code/Phase1` folder.

This will result in all resulting images given in the report in the `./Code/Phase1` folder.

Phase 2 : NeRF

Go to the `./Code/Phase2` folder
Run `wget http://cseweb.ucsd.edu/~viscomp/projects/LF/papers/ECCV20/nerf/tiny_nerf_data.npz` to get the data file used for NeRF training.
Run `python3 nerf.py`

This will result in the test images predicted and shown in the report.


### Structure from Motion ###

RANSAC

<p align="center">
  <img width="600" height="300" src="https://user-images.githubusercontent.com/55713396/217652416-38f74c01-9a02-4506-80f9-c58c6279b582.png">
</p>


4 Sets of World Points
<p align="center">
  <img width="400" height="300" src="https://user-images.githubusercontent.com/55713396/217653636-825f3ac8-776e-4d50-a434-4729dc94af50.png">
</p>

Disambiguated Best World Points
<p align="center">
  <img width="400" height="300" src="https://user-images.githubusercontent.com/55713396/217653635-be75763f-e1e8-4bc0-891a-6a112596b985.png">
</p>

Non-Linear Triangulation vs Linear Triangulation
<p align="center">
  <img width="400" height="300" src="https://user-images.githubusercontent.com/55713396/217653634-1ecd1f9f-574d-4ba1-8769-ddb310030e94.png">
</p>



