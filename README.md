# Recognition-of-eye-diseases-with-neural-networks

#### This project involves the development of a convolutional neural network (CNN) for detecting ocular diseases using the ODIR-5K database from the Kaggle platform. The CNN was designed using Python, utilizing the Numpy and Keras libraries. The model achieved an accuracy of 89.2% in detecting various ocular diseases such as diabetic retinopathy, cataracts, glaucoma, and age-related macular degeneration.
#### Data augmentation was applied to increase the number of samples for underrepresented classes. Additionally, image formatting and data cleaning were carried out to ensure the consistency and quality of the dataset.

## Processing

From the dataset we select the following labels:

*   Normal (N)
*   Diabetes (D)
*   Glaucoma (G)
*   Cataract (C)
*   Age-related macular degeneration (M)
*   Hypertension (H)
*   Myopia (M)

### Contrast modification
#### First, the contrast of the images was modified with the contrast-limited adaptive histogram equalization (CLAHE) method.
<img src="https://github.com/alexisanzaldo/Recognition-of-eye-diseases-with-neural-networks/blob/main/images/original.png" width=35% height=35%> <img src="https://github.com/alexisanzaldo/Recognition-of-eye-diseases-with-neural-networks/blob/main/images/Clahe.png" width=35% height=35%>

### Data distribution
#### Then, the data were augmented with random rotation, zoom-in, zoom-out, brightness, horizontal flip, and vertical flip.
<img src="https://github.com/alexisanzaldo/Recognition-of-eye-diseases-with-neural-networks/blob/main/images/originaldata.png" width=35% height=35%> <img src="https://github.com/alexisanzaldo/Recognition-of-eye-diseases-with-neural-networks/blob/main/images/augmenteddata.png" width=35% height=35%>

### Example of the final images
<img src="https://github.com/alexisanzaldo/Recognition-of-eye-diseases-with-neural-networks/blob/main/images/training_images.png" width=55% height=55%>

### Results
<img src="https://github.com/alexisanzaldo/Recognition-of-eye-diseases-with-neural-networks/blob/main/images/results.png" width=55% height=55%> 

