# DCGANs for Image Enhancement
Metis Project #5 - Deep convolutional generative adversarial network for image enhancement

For a general overview of GANs, see (this)[] presentation. 
Please see (this)[https://github.com/K-Du/Generative-Adversarial-Network/blob/master/Image%20Enhancement%20Using%20Deep%20Learning.pdf] presentation for a summary of this project.


Instructions:  
- Place all the images in a folder named "dataset". They must be .jpeg format. 
- From a console, run `python srez_main.py` to start training. Results will be automatically stored in a folder called "train", checkpoints will be automatically stored in a 
- By default, the batch size is set to 16 and training will stop after 20 minutes. These and many more settings (see srez_main.py) can be adjusted by appending flags when running the python script.  
For example: `python srez_main.py --batch_size 32 --train_time 60 `


Based on David Garcia's (code)[https://github.com/david-gpu/srez] for enhancing celebrity photos. 
I added features which allows it to be used for images not from the celebrity dataset. 

Todo:
Enable a pure black-and-white mode to increase training speed
Automatically detect objects in a large image and crop out the background

[References](References.md)

