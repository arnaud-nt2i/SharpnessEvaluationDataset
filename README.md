# SharpnessEvaluationDataset
SharpnessReclassificationDataset  contains three data folders, each representing a different scene or subject, with images defocused using a constant defocus step.

Chart and Tools Folder: Contains images defocused on one side (focus toward the camera).

Smear Folder: Contains 10 images from each side of the optimal focus. Image 0 is the best focus. Negative numbers from 0 are increasingly defocused images from one side, while increasingly positive numbers from 0 are defocused images from the other side.

Those images are used to demonstrate the effectiveness of a new sharpness evaluation tool within the logarithmic image processing framework (LIP), enabling the reclassification of images based on sharpness and paving the way for new autofocus tools.

Stay tuned for upcoming publications that cite this dataset.
