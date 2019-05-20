# Aerial Cactus Identification

Model built for [Aerial Cactus Identification](https://www.kaggle.com/c/aerial-cactus-identification/data)

This competition is based on resesearch previously hosted on kaggle; original dataset found [here](https://www.kaggle.com/irvingvasquez/cactus-aerial-photos) 

Objective of the problem is to identify whether aerial images contain columnar cacti. 

Example images for classification:

- Cacti: 

<a href="Cacti"><img src="/images/0004be2cfeaba1c0361d39e2b000257b.jpg" align="center" height="100" ></a>

- No Cacti: 

<a href="No Cacti"><img src="/images/002134abf28af54575c18741b89dd2a4.jpg" align="center" height="100" ></a>


For an initial attempt, I explored using a frozen [VGG16](https://arxiv.org/abs/1409.1556) base model pretrained on the [ImageNet](http://www.image-net.org) dataset. 


<a href="Loss + Accuracy"><img src="/images/acc.png" align="left" width="700" ></a>
