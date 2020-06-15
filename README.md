# Dynamic Fluid Surface Reconstruction Using Deep Neural Network
#### [Project Page](https://ivlab.cse.lsu.edu/FSRN_CVPR20.html) | [Paper](https://ivlab.cse.lsu.edu/pub/fluid_cvpr20.pdf)
[Simron Thapa](https://simronthapa.github.io/), [Nianyi Li](https://sites.duke.edu/nianyi/), [Jinwei Ye](https://ivlab.cse.lsu.edu/), Imaging and Vision Lab, Louisiana State University. In CVPR 2020 (oral).

<img src="./img/3092-teaser.gif" width="200">

We present a dynamic fluid surface reconstruction network that recovers time-varying 3D fluid surfaces from a single viewpoint.

## Contributions
1. We design physics-motivated loss functions for network training
2. We synthesize a large fluid dataset using physics-based modeling and rendering
3. Our network is validated on real captured fluid data

## Datasets
[Training](), [Validation](), [Testing]()

Please remember to cite the paper if you use this dataset.

## Training and Testing
The data preprocessing code (before training with FSRN-CNN) and data post-processing code for the predictions (before training with FSRN-RNN) will be made available soon.
```
python FSRN-CNN-train.py
python FSRN-RNN-train.py
```

## Evaluation
The code for evaluating the predictions with ground truth values. We use accuracy and error matrics.
```
python evaluate_metrics.py
```
## Results
1. Synthetic results

<p float="left">
  <img src="./img/syn.gif" width="500" />
  <img src="./img/syn1.gif" width="500" /> 
</p>

2. Real Results

<p float="left">
  <img src="./img/real.gif" width="500" />
  <img src="./img/real1.gif" width="500" /> 
</p>


## Citation
```
@InProceedings{Thapa_2020_CVPR,
author = {Thapa, Simron and Li, Nianyi and Ye, Jinwei},
title = {Dynamic Fluid Surface Reconstruction Using Deep Neural Network},
booktitle = {The IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
month = {June},
year = {2020}
}
```
