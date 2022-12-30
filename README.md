# DyVRNN
This repository contains a PyTorch implementation of DyVRNN (DYnamic mixture Variational Graph Recurrent Neural Networks) for dynamic graph representation Learning.
![overalView](https://user-images.githubusercontent.com/91316109/210011672-3e782c02-4bcf-47aa-a882-916eaf79502d.jpg)

# Requirements
- Pytorch
  - !pip install torch-scatter
  - !pip install torch-sparse
  - !pip install torch-cluster
  - !pip install torch-spline-conv 
  - !pip install torch-geometric==1.0.2
  - !pip install torchvision
- python 3.x
- networkx
- scikit-learn
- scipy
# Repository Organization
- ``` input_data.py ```
- ``` preprocessing.py ```
- ``` DyVG.py ```
# Cite
Please cite our paper if you use this code in your own work:
```
@article{niknamshirvan4225824dyvgrnn,
  title={DyVGRNN: DYnamic Mixture Variational Graph Recurrent Neural Networks},
  author={Niknamshirvan, Ghazaleh and Molaei, Soheila and Zare, Hadi and Pan, Shirui and Clifton, David A and Jalili, Mahdi},
  journal={Available at SSRN 4225824}
}
```
