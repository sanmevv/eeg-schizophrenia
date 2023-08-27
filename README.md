# Detection of schizophrenia from EEG signals using deep learning.

Schizophrenia is a complex mental disorder that necessitates early detection and accurate diagnosis for effective treatment. This research paper proposes an approach for comparison of performance of deep learning models in schizophrenia detection. The three different models used: VGG16, CNN, and LSTM. Each model will be evaluated separately to assess its performance on the task. The VGG16 architecture will be utilized to extract high-level features from neuroimaging data, while the CNN model will focus on learning spatial patterns. The LSTM layers will capture temporal dependencies in the data. Each model will undergo individual training and evaluation on a large dataset, allowing for a comprehensive analysis of their performance in accurately distinguishing between individuals with schizophrenia and healthy controls. By comparing the results obtained from each model, valuable insights into their relative strengths and weaknesses can be gained. This comparative study will provide a comprehensive understanding of the capabilities and limitations of each model in the context of schizophrenia detection, contributing to the advancement of diagnostic approaches in the field. summarize these in a few points

This study presents an evaluation of the accuracy and performance of different models, namely VGG16-CNN, Basic Convolutional Neural Networks (CNN), and Long Short-Term Memory (LSTM), for the detection of schizophrenia using EEG data from adolescents. The dataset consists of EEG records from two groups: healthy controls and individuals with symptoms of schizophrenia. The aim is to systematically test and compare the performance of each model in accurately distinguishing between the two groups. By conducting a comparative study, this study seeks to gain insights into the strengths and limitations of each model in detecting schizophrenia based on EEG data. The findings will contribute to a better understanding of the suitability and effectiveness of these models in the context of schizophrenia detection, which will facilitate future research and the development of improved diagnostic approaches for this mental disorder, with the potential to aid early detection and intervention by clinicians and ultimately improve outcomes for patients with schizophrenia.

## WORKFLOW:
- Collected EEG data on schizophrenia from credible sources.
- Applied suitable filtering techniques to remove noise and artifacts from the EEG data.
- Partitioned the data into shorter epochs [1] for simplifying analysis.
- Generated spectrogram pictures from pre-processed EEG data using the Short-Time Fourier Transform (STFT).
- Divided the dataset into training, validation, and testing sets.
- Trained deep learning models such as Basic CNN, VGG16, and LSTM using the spectrogram pictures and fine-tune hyperparameters.
- Evaluated the performance of each trained model using the validation set and relevant performance indicators (accuracy, precision, recall, and F1-score).
- Selected the model with the highest accuracy as the best performer.
- Assessed the chosen model's performance using the testing set.
- Analysed the outcomes and drew inferences based on model training and testing.
- Identified any study limitations and provided recommendations for further research.
