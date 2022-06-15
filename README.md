# Computer-vision-Object-Detection
The project's goal is to find images of individuals wearing masks.

Methods:

The method count masks(dataset) calculates the number of faces in the list of pictures dataset that are properly wearing masks (with mask class), without masks (without mask class), and erroneously wearing masks 
(mask_weared incorrect_class) in the MaskedFaceTestDataset class. The goal is to create a masked face detector with three classes (4th class being the background) that can detect the aforementioned kinds of objects in a given picture.

Inputs:

• dataset is a MaskedFaceTestDataset class object.

Output:

This function should return a 2 dimensional numpy array of shape 𝑁×3N×3 of data type int64 whose values should respectively indicate the number of faces wearing mask, without mask and incorrectly wearing mask.
