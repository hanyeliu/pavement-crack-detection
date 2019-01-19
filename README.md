# pavement-crack-detection
The project is used to share our recent work on pavement crack detection. For the details of the work, the readers are refer to the paper "Feature Pyramid and Hierarchical Boosting Network for Pavement Crack Detection" (FPHB).
You can find the paper in https://www.researchgate.net/publication/330244656_Feature_Pyramid_and_Hierarchical_Boosting_Network_for_Pavement_Crack_Detection.

The datasets used in paper, crack detection results on each datasets, and pretrained model are stored in https://drive.google.com/open?id=1y9SxmmFVh0xdQR-wdchUmnScuWMJ5_O-.
# Installing
1. install HED, follow the link https://github.com/s9xie/hed.
2. put CustomSigmoidCrossEntropyLossLayer.py in hed/python folder
3. put the *prototxt files in hed/example/hed folder

# Training and Test
The training and test steps are same with HED, please read the instruction in https://github.com/s9xie/hed.

If you encounter any issue when using our code or model, please let me know.

# Note: please cite the corresponding papers when using these datasets.

CRACK500: @inproceedings{zhang2016road,
  title={Road crack detection using deep convolutional neural network},
  author={Zhang, Lei and Yang, Fan and Zhang, Yimin Daniel and Zhu, Ying Julie},
  booktitle={Image Processing (ICIP), 2016 IEEE International Conference on},
  pages={3708--3712},
  year={2016},
  organization={IEEE}
}

GAPs384: @inproceedings{eisenbach2017how,
  title={How to Get Pavement Distress Detection Ready for Deep Learning? A Systematic Approach.},
  author={Eisenbach, Markus and Stricker, Ronny and Seichter, Daniel and Amende, Karl and Debes, Klaus
          and Sesselmann, Maximilian and Ebersbach, Dirk and Stoeckert, Ulrike
          and Gross, Horst-Michael},
  booktitle={International Joint Conference on Neural Networks (IJCNN)},
  pages={2039--2047},
  year={2017}
}

CFD: @article{shi2016automatic,
  title={Automatic road crack detection using random structured forests},
  author={Shi, Yong and Cui, Limeng and Qi, Zhiquan and Meng, Fan and Chen, Zhensong},
  journal={IEEE Transactions on Intelligent Transportation Systems},
  volume={17},
  number={12},
  pages={3434--3445},
  year={2016},
  publisher={IEEE}
}

AEL: @article{amhaz2016automatic,
  title={Automatic Crack Detection on Two-Dimensional Pavement Images: An Algorithm Based on Minimal Path Selection.},
  author={Amhaz, Rabih and Chambon, Sylvie and Idier, J{\'e}r{\^o}me and Baltazart, Vincent}
}

cracktree200: @article{zou2012cracktree,
  title={CrackTree: Automatic crack detection from pavement images},
  author={Zou, Qin and Cao, Yu and Li, Qingquan and Mao, Qingzhou and Wang, Song},
  journal={Pattern Recognition Letters},
  volume={33},
  number={3},
  pages={227--238},
  year={2012},
  publisher={Elsevier}
}


