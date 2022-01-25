# SOLO

We implement SOLO with a category and mask branch for segmentation. We assign each instance to a grid cell based on instance's location and size. 

## Model Architecture

![Screen Shot 2022-01-25 at 4 40 10 AM](https://user-images.githubusercontent.com/40223805/150951584-b22ac9d1-e471-4a2c-bdff-de3429863c57.png)


## Training Details

Training was done for 36 epochs as recommended. We used an 80/20 split of
the dataset for training and testing. The learning rate was amended to count
for the decrease in batch size as compared to the original SOLO paper. We used
a training batch size of 4 and an initial learning rate of 0.0025. The learning
rate scheduler was set up to match the original setup.

# Results

![Screen Shot 2022-01-25 at 4 35 33 AM](https://user-images.githubusercontent.com/40223805/150951703-f437410e-35e8-49db-aef2-dcc4a6d499e6.png)![Screen Shot 2022-01-25 at 4 35 39 AM](https://user-images.githubusercontent.com/40223805/150951735-e6257913-3e46-4c73-87e8-e3d3f61105a0.png)![Screen Shot 2022-01-25 at 4 35 50 AM](https://user-images.githubusercontent.com/40223805/150951745-0b8de525-46db-4356-b1d1-2c3677d185b2.png)


