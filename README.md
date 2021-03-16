## How old is your brain?

The task is to design an ML model that can accurately predict the age of
a person based on their brain MRI scan. An application of such a network
can be detecting discrepancy between person's age and their brain age which
could be indicative of abnormalities in cognitive aging.


The developed model is a 3D convolutional neural network (CNN) with a custom
architecture based on the VGG-net implemented in PyTorch. After 30 epochs of
training, the CNN is able to predict the age with an average error of 5.18 years.
The MRI scans and visualisations were supplied by Imeprial College London.

![BlehNet Architecture](https://github.com/marektopolewski/how-old-is-your-brain/blob/main/blehNet.png)
