# DCGAN_Descriptor
- Training module for DCGAN (main.py)
- Descriptor extraction from DCGAN (Extracting_DCGAN_features.ipynb)
- Checkpoint file for our DCGAN model trained on Places dataset (checkpoint/PatchofPlaces_128_64_64)

# Feature extraction
If you want to extract our DCGAN feature from the trained network, please check `Extracting_DCGAN_features.ipynb` file.

# Training dataset
- We used the Places dataset for the training the DCGAN.
http://places2.csail.mit.edu/
From this dataset, we generated 64X64 size of local patch images from each image.
And then we trained the DCGAN model on the local patch images.
If you want to train the model on your training data, run the following commend after constructing your training dataset. 

`python main.py --dataset "path/to/dataset" --input_height=64 --batch_size=128 --train`

# Constructing your training dataset
(To be added)

# Evaluation dataset
- The following link is for the evaluation datset for our loop closure detection method.
https://github.com/JustWon/LCD_Dataset

# Dependencies
- Python 3
- Numpy
- Tensorflow


# Reference
https://github.com/carpedm20/DCGAN-tensorflow

# Contact
- If you have any comments, please make a thread on an issues page or contact dongwonshin@gist.ac.kr.
