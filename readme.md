# CLASIFICATION TEST STATS
| Model |  Loss | F1 score | Accuracy | Recall | Precision |
| --- |  --- | --- | --- | --- | --- |
| Clasification based on raw image  | 0.267 | 0.895 | 0.914 | 0.866 | 0.946 |
| Clasification based on procesd image  | 0.203 | 0.915 | 0.929 | 0.850 | 0.999 |
| Clasification based on  binary vessel map | 0.419 | 0.843 | 0.829 | 0.866 | 0.829 |


# SEGMENTATION TEST STATS
| Model | Loss | Iou score | F1 score | Accuracy | Recall | Precision | Specificity |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Segmentation based on raw image without augmentation | 0.200 | 0.670 | 0.797 | 0.970 | 0.776 | 0.825 | 0.986|
| Segmentation based on raw image with augmentation | 0.199 | 0.675 | 0.801 | 0.970 | 0.801 | 0.807 | 0.983 |
| Segmentation based on procesd image  without augmentation | 0.195 | 0.678 | 0.802 | 0.971 | 0.785 | 0.825 | 0.986|
| Segmentation based on procesd image with augmentation | 0.200 | 0.670 | 0.797 |0.971 | 0.772 | 0.829 | 0.986|

# PLOTS
## Clasification based on raw image
![alt text](https://github.com/Mpasiowiec/Retinopatia/blob/main/densenet/models/densenet121_e20_s300_b14_plot.jpg?raw=true)
![alt text](https://github.com/Mpasiowiec/Retinopatia/blob/main/densenet/models/densenet121_e20_s300_b14_viz.jpg?raw=true)
## Clasification based on procesd image
![alt text](https://github.com/Mpasiowiec/Retinopatia/blob/main/densenet/models/densenet121_prep_e20_s300_b14_plot.jpg?raw=true)
![alt text](https://github.com/Mpasiowiec/Retinopatia/blob/main/densenet/models/densenet121_prep_e20_s300_b14_viz.jpg?raw=true)
## Clasification based on  binary vessel map
![alt text](https://github.com/Mpasiowiec/Retinopatia/blob/main/densenet/models/densenet121_vessel_e20_s300_b14_plot.jpg?raw=true)
![alt text](https://github.com/Mpasiowiec/Retinopatia/blob/main/densenet/models/densenet121_vessel_e20_s300_b14_viz.jpg?raw=true)

## Segmentation based on raw image
### without augmentation
![alt text](https://github.com/Mpasiowiec/Retinopatia/blob/main/unet/models/UNet11_e40_s256_b9_noaugm_plot.jpg?raw=true)
![alt text](https://github.com/Mpasiowiec/Retinopatia/blob/main/unet/models/UNet11_e40_s256_b9_noaugm_viz.jpg?raw=true)
### with augmentation
![alt text](https://github.com/Mpasiowiec/Retinopatia/blob/main/unet/models/UNet11_e40_s256_b9_jit_plot.jpg?raw=true)
![alt text](https://github.com/Mpasiowiec/Retinopatia/blob/main/unet/models/UNet11_e40_s256_b9_jit_viz.jpg?raw=true)
## Segmentation based on procesd image
### without augmentation
![alt text](https://github.com/Mpasiowiec/Retinopatia/blob/main/unet/models/UNet11_prep_e40_s256_b9_noaugm_plot.jpg?raw=true)
![alt text](https://github.com/Mpasiowiec/Retinopatia/blob/main/unet/models/UNet11_prep_e40_s256_b9_noaugm_viz.jpg?raw=true)
### with augmentation
![alt text](https://github.com/Mpasiowiec/Retinopatia/blob/main/unet/models/UNet11_prep_e40_s256_b9_jit_plot.jpg?raw=true)
![alt text](https://github.com/Mpasiowiec/Retinopatia/blob/main/unet/models/UNet11_prep_e40_s256_b9_jit_viz.jpg?raw=true)

