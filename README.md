# MeDAL Retina Dataset
This work is licensed under a CC BY 4.0 license.

Our lab, MeDAL at IITB, has generated this dataset with the aim of assisting researchers in developing algorithms for keypoints detection and pretraining large models on retinal images using a self-supervised approach. The keypoints have been meticulously annotated by students from our lab. To delve deeper into the dataset, we encourage you to refer to our paper, which provides comprehensive details. Paper's Link: https://arxiv.org/pdf/2307.10698.pdf

In the figure bellow, the first and second rows display images from the e-ophtha dataset and the retinal disease classification dataset, respectively, along with our annotations
presented as keypoints overlaid on these images. The third row showcases images from the FIRE dataset, accompanied by the corresponding annotations for reference.

![keypoints](https://github.com/SaharAlmahfouzNasser/MeDAL-Retina/assets/52508554/861e0e57-59a9-4088-b150-bb0a8975fc2e)

You can download the dataset from: https://www.dropbox.com/sh/o8q84e2eg54ay3d/AADiAkNr6bFQDoFaKeEjpYtra?dl=0

The dataset is organized into three folders as follows:

1. Self-Supervision Data: This folder contains images sourced from various publicly available datasets. These images are intended for training the Swin-Transformer in a self-supervised fashion, primarily for tasks like angle of rotation prediction or masked region prediction within input images.

2. Auxiliary Data: In this folder, you'll find images that lack annotations. These images are exclusively used to train the descriptor decoder in an unsupervised manner.

3. Super Retina Training Data: This folder comprises retina images along with their corresponding annotations. These resources are employed for training the keypoint detector.

# Citation
If you find value in utilizing this dataset, we kindly request that you cite it as a reference.

@misc{medal-retina,
  author = {Gupte, Nihar and Almahfouz Nasser, Sahar and Garg, Prateek and Singhal, Keshav and Jain,Tanmay and Aditya and Kumar, Ravi and Sethi, Amit},
  title = {{MeDAL-Retina}},
  howpublished = {\url{https://www.dropbox.com/sh/o8q84e2eg54ay3d/AADiAkNr6bFQDoFaKeEjpYtra?dl=0}},
  year = {2023},
  note = {Dataset},
}


Gupte, N., Almahfouz Nasser, S., Garg, P., Singhal, K., Jain, T., Aditya, Kumar, R., & Sethi, A. (2023). MeDAL-Retina [Dataset]. Retrieved from [https://www.dropbox.com/sh/o8q84e2eg54ay3d/AADiAkNr6bFQDoFaKeEjpYtra?dl=0]


