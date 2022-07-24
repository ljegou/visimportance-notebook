# Predicting Visual Importance Across Graphic Design Types : Jupyter Notebook version

To execute the iPython Notebook in a Binder Jupyter : [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/transcarto/predimportance-public/HEAD)

### Source code by Zoya Bylinskii et al. with Caffe AI models : https://github.com/cvzoya/visimportance

The paper : https://dl.acm.org/doi/abs/10.1145/3126594.3126653

> @inproceedings{10.1145/3126594.3126653,
author = {Bylinskii, Zoya and Kim, Nam Wook and O'Donovan, Peter and Alsheikh, Sami and Madan, Spandan and Pfister, Hanspeter and Durand, Fredo and Russell, Bryan and Hertzmann, Aaron},  
title = {Learning Visual Importance for Graphic Designs and Data Visualizations},  
year = {2017},  
isbn = {9781450349819},  
publisher = {Association for Computing Machinery},  
address = {New York, NY, USA},  
url = {https://doi.org/10.1145/3126594.3126653},  
doi = {10.1145/3126594.3126653},  
abstract = {Knowing where people look and click on visual designs can provide clues about how the designs are perceived, and where the most important or relevant content lies. The most important content of a visual design can be used for effective summarization or to facilitate retrieval from a database. We present automated models that predict the relative importance of different elements in data visualizations and graphic designs. Our models are neural networks trained on human clicks and importance annotations on hundreds of designs. We collected a new dataset of crowdsourced importance, and analyzed the predictions of our models with respect to ground truth importance and human eye movements. We demonstrate how such predictions of importance can be used for automatic design retargeting and thumbnailing. User studies with hundreds of MTurk participants validate that, with limited post-processing, our importance-driven applications are on par with, or outperform, current state-of-the-art methods, including natural image saliency. We also provide a demonstration of how our importance predictions can be built into interactive design tools to offer immediate feedback during the design process.},  
booktitle = {Proceedings of the 30th Annual ACM Symposium on User Interface Software and Technology},  
pages = {57–69},  
numpages = {13},  
keywords = {machine learning, computer vision, graphic design, visualization, deep learning, retargeting, saliency, eye tracking},  
location = {Qu\'{e}bec City, QC, Canada},  
series = {UIST '17}  
}

- Adapted by Egor Abaturov to use PyTorch : https://github.com/egorabaturov/visimportance-in-pytorch
- Converted to iPython Jupyter Notebook by L. Jégou
