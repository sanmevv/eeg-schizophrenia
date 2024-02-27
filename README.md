#### Spectral and graph-based deep learning models for schizophrenia detection(EEG data)
* Published research paper on IEEE Xplore; explore the content at : https://ieeexplore.ieee.org/document/10434266
##### Problem statement:
* Accurately detecting and classifying schizophrenia in adolescents using EEG data.

* Assessing the performance of deep learning models in distinguishing between healthy individuals and those with schizophrenia.

* Understanding the effectiveness of these models in analyzing EEG data for diagnostic purposes.

* Exploring unconventional methods (FFT/STFT and Laplace Transform) for EEG signal preprocessing in schizophrenia detection.

* Improving diagnostic approaches for early schizophrenia detection and intervention.

##### Conclusion
* The study's primary goal was to determine if a subject has schizophrenia using EEG data, applying unconventional methods like spectrogram conversion and Laplace Transform preprocessing followed by GraphCNN.

* FFT preprocessing with VAE achieved 96.50% accuracy, while STFT preprocessing with VGG-16, a pre-trained CNN model, yielded the highest accuracy at 97.22%, indicating its effectiveness and stability in processing EEG signals.

* The second approach using GraphCNN, designed to identify spatial and temporal patterns in EEG data, achieved an accuracy of 87.5%, though lower compared to other models, potentially due to model fine tunes or transformation issues.
