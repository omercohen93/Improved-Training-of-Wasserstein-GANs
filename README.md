# Improved-Training-of-Wasserstein-GANs
implementation of the architecture designed for CIFAR10 from "Improved Training of Wasserstein GANs" by Gulrajani.

This folder present an easy to use colab notebooks, suitable for working with files inside your google drive.
The Data used in this code is 'FASHION MNIS'.
The Gradient Penalty method described in the paper was used on WGAN.
The training process for WGAN with gradient penalty and DCGAN took 50 epochs. It took 2-3 trials to train DCGAN and get descent results, and it took 3-4 trials for WGAN with gradient penalty.
The results we got:
![image](https://user-images.githubusercontent.com/73498160/111076658-e47a3400-84f5-11eb-8aa9-be569cd6389c.png)

![image](https://user-images.githubusercontent.com/73498160/111076667-efcd5f80-84f5-11eb-8112-32fd5c310f1c.png)


##Real images:
![image](https://user-images.githubusercontent.com/73498160/111076735-3327ce00-84f6-11eb-82e4-8724005f1624.png)

##DCGAN generated images:
![image](https://user-images.githubusercontent.com/73498160/111076747-3f139000-84f6-11eb-89ac-be3a607f6113.png)

##WGAN generated images:
![image](https://user-images.githubusercontent.com/73498160/111076751-476bcb00-84f6-11eb-914d-4348f4bf0cac.png)



## Run in google drive using colab
If your folder is located in an inner folder inside your drive, please specify that path in “Mount drive” part inside “path”.
To test the models and generate new images just run all the notebook. 
To see the training process please delete the relevant hash in “train and test” section.
To see the graph of the training process if you choose to train, please delete the hash in “show training graph” part. 
