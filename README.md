# Rotation representations

This repository contains IPython notebooks for Euler angles visualizations and for regression performance evaluation of Euler angles, quaternions and 6D representations. For more information please visit this [blog post](https://medium.com/@dkostyaev/better-rotation-representations-for-accurate-pose-estimation-e890a7e1317f)


## Performance evalution notebook

To run `rotations_performance.ipynb` you need:

1. [Tensorflow 2](https://www.tensorflow.org).
2. [Pyquaternion](https://github.com/KieranWynn/pyquaternion)

![plot](assets/plot180.png)


## Visualization and rendering notebook

To run `euler_visualization.ipynb` you need to:

1. Request and download [FLAME model](https://flame.is.tue.mpg.de/)
2. Install [simple_camera](https://github.com/kostyaev/simple_camera) library to render triangle meshes.
3. Install [Moviepy](https://github.com/Zulko/moviepy)

![animation](assets/ypr_anim_optim.gif)



[![license](https://img.shields.io/github/license/DAVFoundation/captain-n3m0.svg?style=flat-square)](https://github.com/DAVFoundation/captain-n3m0/blob/master/LICENSE)
