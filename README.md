# COVID-19 Transfer Learning Using Lung Images
With the emergence of COVID-19, several teams of researchers are developing
models to detect viral presence in the lungs of patients. However, there are still
few X-ray images available. We employ transfer learning, using several pretrained
models to determine which model is most suitable as well as preprocess these
images to determine how accuracy can be improved on the currently available
small datasets. Using Grad-CAM, we verified which parts of the images were
taken into account for the classification. We found that VGG16 was the best model
for this problem out of the ones we used, and that we were able to improve the
accuracy by preprocessing the images. After analyzing the images with Grad-CAM
we determined that any model trained solely on this dataset is not suitable for
medical applications.

