---
title: ttach
categories: ['python', 'augmentation', 'deep-learning']
---
## [ttach](https://github.com/qubvel/ttach)

### Image Test Time Augmentation with PyTorch!

Image Test Time Augmentation with PyTorch!

Similar to what Data Augmentation is doing to the training set, the purpose of Test Time Augmentation is to perform random modifications to the test images. Thus, instead of showing the regular, “clean” images, only once to the trained model, we will show it the augmented images several times. We will then average the predictions of each corresponding image and take that as our final guess [[1](https://towardsdatascience.com/test-time-augmentation-tta-and-how-to-perform-it-with-keras-4ac19b67fb4d)].  
```
           Input
             |           # input batch of images 
        / / /|\ \ \      # apply augmentations (flips, rotation, scale, etc.)
       | | | | | | |     # pass augmented batches through model
       | | | | | | |     # reverse transformations for each batch of masks/labels
        \ \ \ / / /      # merge predictions (mean, max, gmean, etc.)
             |           # output batch of masks/labels
           Output
```