# Audio-Feature-Engineering
## I. Introduction
In this repository we will talk about the various transformations that can be applied to audio signals. Most of these transformations convert audio to image so that Convolution Layers can be used to extract features.The main advantage of converting to image is that there is more raw features available to perform deep learning algorithms on them.
Feature Engineering is a crucial role in any data science project. Better choice of features implies simpler models , faster training , better accuracy, and overall efficeint workflow.
## II. Audio Features
A variety of features can be extracted from audio signals. Based of the domain specificity, we can classify them as :-
1. Time Domain Features
2. Frequency Domain Features
3. Time-Frequency Domain Features

##### Time Domain Features:
Time domain features includes quantities like pitch,zero cross-over,envelop,etc.These features are robust and best suited for ML based approaches.
##### Frequency Domain Features:
Frequency domain features are obatained by tranforming the time domain signal to frequency domain.These features are not practically understood but have real significance as they carry valuable information about the signal.DFT Spectrum is an example of frequency domain feature.
