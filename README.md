The Sharpness Reclassification Dataset contains two data folders:

"Defocus": Depicts different scenes with images defocused using a constant defocus step.
- Chart and Tools Folder: Contains images defocused on one side (focus toward the camera).
- Smear Folder: Contains 10 images from each side of the optimal focus. Image 0 is the best focus. Negative numbers from 0 are increasingly defocused images from one side, while increasingly positive numbers from 0 are defocused images from the other side.

"Defocus & Expo":
- Tools: Contains 50 images, with 10 defocused steps using a constant defocus step. For each step, 5 exposures have been recorded.

These images are used to demonstrate the effectiveness of a new sharpness evaluation tool within the logarithmic image processing framework (LIP).

For each image folder, there is an associated mlac folder. This folder contains the Maximal Logarithmic Additive Contrast (MLAC) map corresponding to each image. The mean value of this map serves as a reliable evaluation of the image's sharpness. This tool enables the reclassification of images based on sharpness and paves the way for new autofocus tools.

Stay tuned for upcoming publications that cite this dataset.
