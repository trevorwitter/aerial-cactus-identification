# Aerial Cactus Identification

Model built for [Aerial Cactus Identification](https://www.kaggle.com/c/aerial-cactus-identification/data)

This competition is based on resesearch previously hosted on kaggle; original dataset found [here](https://www.kaggle.com/irvingvasquez/cactus-aerial-photos) 

Objective of the problem is to identify whether aerial images contain columnar cacti. 

Example images for classification:

- Cacti: 

![Cacti](/images/0004be2cfeaba1c0361d39e2b000257b.jpg =300x)

- No Cacti: 

![No Cacti](/images/002134abf28af54575c18741b89dd2a4.jpg =300x)

For an initial attempt, I explored using a frozen [VGG16](https://arxiv.org/abs/1409.1556) base model pretrained on the [ImageNet](http://www.image-net.org) dataset. 

![Loss + Accuracy](/images/acc.png =50x)
