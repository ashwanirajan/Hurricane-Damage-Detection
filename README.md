# Hurricane Damage Detection

We used Transfer Learning with the help of Fastai module to build a classifier which can distinguish damaged and non-damaged buildings from their satellite images. Using resnet-34, we could reach an accuracy of 99.75% on our test dataset. Please refer to results.pdf to have a look at the confusion matrix and sample results. It also has the top 9 samples which contribute maximum to the loss.\

The cutout image dataset that we used to train and test our model can be obtained from https://github.com/qcao10/DamageDetection. Thanks to Quoc Dung Cao et al(https://arxiv.org/pdf/1807.01688.pdf) for open-sourcing the dataset.
