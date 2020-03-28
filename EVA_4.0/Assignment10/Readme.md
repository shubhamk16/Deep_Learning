# About assignment-10
1. CIFAR10 Model using Resnet18 network architetcure
2. Data augmentation using albumentations library - applied cutout data augmentation
3. LRFinder to get the lr range estimate for model training
4. ReduceLrOnPlateu is applied to reduce LR when model get stuck in Plateu region
5. GradCAM for 25 misclassified images

## Sample images of albumentations augmentation
### Data Augmentation technique: Horizontalflip, CoarseDropout
![github-small](https://github.com/BirenderPanwar/EVA4_Phase1/blob/master/session10/images/albumentations_images.png)

## some images which model fails to predict
![github-small](https://github.com/BirenderPanwar/EVA4_Phase1/blob/master/session10/images/model_misclassified.png)

## LR_finder
![github-small](https://github.com/BirenderPanwar/EVA4_Phase1/blob/master/session10/images/lr_finder.png)

## Epoch vs. Accuracy plot
![github-small](https://github.com/BirenderPanwar/EVA4_Phase1/blob/master/session10/images/model_history.png)

## Gradcam ![github-small](https://github.com/BirenderPanwar/EVA4_Phase1/blob/master/session10/images/gradcam_result_details.png)
