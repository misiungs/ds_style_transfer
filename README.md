# Style transfer
Application of style transfer to a chosen photography.

<img src="https://github.com/misiungs/readme_images/blob/master/paint.jpg?raw=true" alt="drawing" width="500"/>

# Problem
The goal of this project is to transfer style of a chosen painting into a selected photography.
In that way two images are blended together and the content of the photography is depicted as "painted" in the style of reference image.

# Approach
Transfer style is done with the pretrained VGG-19 network.
Based on it separate loss functions for content and style are formulated using selected intermediate layers.
The influence of each layer on the output image is studied and few additional improvements are proposed to enhance the quality of image.

# Conclusions
The style and content image has been mixeg giving (subjectively) satisfying results.

