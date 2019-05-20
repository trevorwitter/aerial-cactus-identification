# Aerial Cactus Identification

Model built for [Aerial Cactus Identification](https://www.kaggle.com/c/aerial-cactus-identification/data)

This competition is based on resesearch previously hosted on kaggle; original dataset found [here](https://www.kaggle.com/irvingvasquez/cactus-aerial-photos) 

Objective of the problem is to identify whether aerial images contain columnar cacti. 

Example images for classification:

- Cacti: 

<p align="center"><a href="Cacti"><img src="/images/0004be2cfeaba1c0361d39e2b000257b.jpg" align="center" height="100" hspace="5"></a><a href="Cacti"><img src="/images/0017c3c18ddd57a2ea6f9848c79d83d2.jpg" align="center" height="100"></a>
<a href="Cacti"><img src="/images/003ec9bcef67171ba49fe4c3b7c80aec.jpg" align="center" height="100" hspace="5"></a><a href="Cacti"><img src="/images/003ec9bcef67171ba49fe4c3b7c80aec.jpg" align="center" height="100"></a></p>

- No Cacti: 

<p align="center"><a href="No Cacti"><img src="/images/002134abf28af54575c18741b89dd2a4.jpg" align="center" height="100" hspace="5"></a><a href="No Cacti"><img src="/images/003bb64852016d9c87871ddd8e25ab03.jpg" align="center" height="100" ></a><a href="No Cacti"><img src="/images/0283336bcc959eb5cdf69b144903a428.jpg" align="center" height="100" hspace="5"></a></p>


#### Transfer Learning
For an initial attempt, I explored using a frozen [VGG16](https://arxiv.org/abs/1409.1556) base model pretrained on the [ImageNet](http://www.image-net.org) dataset. I did not retrain these layer given the similarity of cacti to other objects in the imagenet dataset. 

#### Model Parameters:
<a href="model params"><img src="/images/model_params.png" align="center" width="800" ></a>



#### Score
After 200 training epochs, the model settled at a validation loss of ~0.10 and a validation accuracy of ~0.96
<a href="Loss + Accuracy"><img src="/images/acc.png" align="left" width="700" ></a>
