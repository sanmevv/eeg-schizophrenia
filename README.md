### SPECTROGRAM AND GRAPH-BASED DEEP LEARNING FOR SCHIZOPHRENIA DETECTION FROM EEG SIGNALS

Deep learning has intervened in the field of neuroscience by inspecting activities in the brain through Electroencephalogram (EEG) signals. This research investigates the application of two unconventional preprocessing approaches to EEG signals, aiming to enhance the classification of schizophrenic adolescents from healthy individuals. To analyze the EEG signals, the researchers used three different mathematical techniques called Fourier Transform (FFT), Short-Time Fourier Transform (STFT) and Laplace Transform. These techniques helped to extract important features from the signals, or to identify patterns in the brain activity that could be related to schizophrenia. After extracting the features, the researchers then used them as input for different deep learning models to detect schizophrenia. Deep learning models like CNN, VGG-16, Variational AutoEncoders, GoogLeNet, ChronoNet and GraphCNN were used. It was found that the STFT processed signals on VGG-16 gave the best results. Overall, this study shows that investigating brain activity using EEG signals and using deep learning models can be a useful tool for detecting mental disorders like schizophrenia.


● The research explored various preprocessing techniques for EEG signals, such as Fourier Transform (FFT), Short Time Fourier Transform (STFT), and Laplace Transform, aiming to aid deep learning models in differentiating between adolescents with schizophrenia and healthy controls. These methods were crucial in extracting meaningful patterns and features from the EEG data.

● Among the models tested, the combination of STFT processed signals with the VGG-16 architecture yielded the most promising results, demonstrating its effectiveness in feature extraction and pattern recognition within EEG data indicative of schizophrenia.

● The study also experimented with models like GoogleNet, Variational AutoEncoders, ChronoNet and the application of the Laplace Transform in conjunction with GraphCNN (G-CNN). These models offered alternative approaches to data analysis, each with its unique strengths.

● Notably, the STFT with VGG-16 having an accuracy of 97.22% outperformed the other models, underscoring the potential of this particular combination in schizophrenia detection using EEG data.
