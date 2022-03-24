## Project’s title: Denoising AutoEncoder for dirty documents

## ****Project Description:****

- I did the project using keras functional API and other complimentary libraries
- A convolutional autoencoder with `Trainable params: 220,345` with convolutional, batch normalization, dropout and max pooling layers
- Data augmentation pipeline using **imgaug library,**  3 augmentation types rotation, flipping and perspective transformation
- The augmented training data in feed to the training function using custom generator(sequence)
- I trained the model through 300 epochs with `validation mean absolute error: 0.0099`
- i used adam optimizer with learning rate decay

## My comments:

I used early stopping callback (but the training stopped normally) that is why i belive that increasing the training epochs would result in even lower error

i tried to lower the encoded code size but some distortion in the text itself would appear

## Some Results:

![result.png](reuslt.png)
