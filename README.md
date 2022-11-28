# puncta-segmentation

This [KNIME](https://www.knime.com/) workflow segments puncta from single channel 2D images. Briefly, input images are blurred using a Gaussian filter, subtracted form the original image (leaving the puncta signal), applied a thresold and labaled with a conncted component analysis (eight-connected). 

**puncta-segmentation workflow**
![workflow](doc/images/workflow_map.svg)

## Example images
View of input sample image:
![input](doc/images/readme_1.png)

View of output sample image with detections/labels:
![output](doc/images/readme_2.png)