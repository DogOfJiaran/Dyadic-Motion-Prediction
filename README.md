# Dyadic Motion Prediction

Collect recent works on dyadic human motion prediction (multi-person human motion predction) and datasets which contain multiple persons

If you find some overlooked papers, please open issues or pull requests.

## Paper

- Isinsu Katircioglu et al., "Dyadic Human Motion Prediction", arXiv 2021.12 [[paper](https://arxiv.org/abs/2112.00396)] 

- Wen Guo et al. "Multi-Person Extreme Motion Prediction", arXiv 2021.05 [[paper](https://arxiv.org/abs/2105.08825)] [[webpage](https://team.inria.fr/robotlearn/multi-person-extreme-motion-prediction/)] [[code](https://github.com/GUO-W/MultiMotion)]

- Jiashun Wang et al., "Multi-Person 3D Motion Prediction with Multi-Range Transformers", NeurIPS 2021 [[paper](https://arxiv.org/abs/2111.12073)] [[webpage](https://jiashunwang.github.io/MRT/)]

- Vida Adeli et al., "Tripod: Human trajectory and pose dynamics forecasting in the wild", ICCV 2020 [[paper](https://arxiv.org/abs/2104.04029)] 

- Vida Adeli et al., "Socially and contextually aware human motion and pose forecasting", RA-L 2020 [[paper](https://arxiv.org/abs/2007.06843)]
 
 
## Datasets

- [[ExPI](https://zenodo.org/record/5578329#.Ya_dA_GZP0r)] 
  - in [Multi-Person Extreme Motion Prediction](https://arxiv.org/abs/2105.08825)
  - dataset: extreme dancing
  - 115 sequences, 16 actions, ~ 30k frames
  - collected by 68 camers, 3D poses infered from markers on the dancers captured by 20 mocap cameras
- [LindyHop600k] (not available yet) 
  - in [Dyadic Human Motion Prediction](https://arxiv.org/abs/2112.00396)
  - dataset: dancing
  - 9 sequences, 4 actions, ~ 40k frames
  - collected by 8 cameras, 3D poses infered from [OpenPose](https://github.com/CMU-Perceptual-Computing-Lab/openpose)
- [CHI3D] (not available since CVPR 2020)
  - in [Three-dimensional Reconstruction of Human Interactions](https://openaccess.thecvf.com/content_CVPR_2020/html/Fieraru_Three-Dimensional_Reconstruction_of_Human_Interactions_CVPR_2020_paper.html)
  - dataset: lab-based accurate 3d motion capture
- [[3DPW](https://virtualhumans.mpi-inf.mpg.de/3DPW/)] 
  - in [Recovering Accurate 3D Human Pose in The Wild Using IMUs and a Moving Camera](https://openaccess.thecvf.com/content_ECCV_2018/html/Timo_von_Marcard_Recovering_Accurate_3D_ECCV_2018_paper.html)
  - dataset: people in the wild
  - 60 sequences, 5 scenarios, ~ 50k frames
  - collected by a moving phone camera, 3D poses infered from their [paper](https://virtualhumans.mpi-inf.mpg.de/papers/vonmarcardECCV18/vonmarcardECCV18.pdf)
- [[MoPoTs](https://vcai.mpi-inf.mpg.de/projects/SingleShotMultiPerson/)] 
  - in [Single-Shot Multi-Person 3D Pose Estimation From Monocular RGB](https://ieeexplore.ieee.org/abstract/document/8490962)
  - dataset: in door and out door scenarios
  - 20 sequences,  ~ 8k frames
  - data and 3D poses are obtained from a multi-view marker-less motion capture system [Captury](https://captury.com/)




