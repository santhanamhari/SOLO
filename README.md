# SOLO

We implement SOLO with a category and mask branch for segmentation. We assign each instance to a grid cell based on instance's location and size. 

## Model Architecture


## Training Details

Training was done for 36 epochs as recommended. We used an 80/20 split of
the dataset for training and testing. The learning rate was amended to count
for the decrease in batch size as compared to the original SOLO paper. We used
a training batch size of 4 and an initial learning rate of 0.0025. The learning
rate scheduler was set up to match the original setup.

# Results





