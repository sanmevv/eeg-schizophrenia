#### A DL-Based Approach for Diagnosis of Schizophrenia using EEG recording of the brain
### Datasets used
A public dataset of SZ EEG recordings was utilized for this project <br> [Dataset](http://brain.bio.msu.ru/eeg_schizophrenia.htm), a 16 channel EEG recording dataset of 84 individuals (45 Schizophernic, 39 Healthy Control) <br> Dataset was divided into 5 second segments of 224x224 spectrogram images of EEG signal.

### Methods
### Plain CNN 
### Plain CNN VGG-16
A VGG-16 CNN architecture implemented in keras was utilized which obtained 96.3% accuracy on test data (100% on training data) <br>
each 5 second sepctrogram of size 224x224 was fed to this network as training data.
this method is based on the work of [Aslan, Akin](http://193.140.240.104/xmlui/handle/11468/7223)
### Hybrid CNN-LSTM
This architecture consists of CNN followed by LSTM cells. inputs of the CNNs are spectrogram segments for one subject, which are fed to LSTM sequentially<br>
This method underperfomrs compared to the previous plain CNN method due to the lack of sufficient training data.<br>
<br>
#### Conclusive Discussion
The evaluation metrics provided of the performance of the above models: VGG16-CNN gave the highest accuracy of 94.44%, while Basic CNN model gave an accuracy of 90.28% and the least was of the LSTM model of as low as 75.0%.
VGG is a complex network architecture with more layers, hence allows it to capture more complex patterns in the EEG signals. The basic CNN was also able to capture some of these patterns, but may not be as effective as VGG due to its simpler architecture. The LSTM, is primarily designed for sequential data and may not be as well-suited to this particular dataset. Moreover, the relatively low accuracy of the LSTM model indicates that spectral information may not be as informative as temporal information in detecting schizophrenia leading to a lower accuracy.

#### Conclusion and Future Scope
● The results obtained by the implementation of the above basic CNN, VGG16 are quite promising and suggest that these models have the potential to be powerful tools in detecting schizophrenia from EEG data.

● The high accuracy of the VGG16 and CNN models demonstrates the effectiveness of using convolutional neural networks for feature extraction from EEG signals. It also suggests that the models have effectively captured the discriminative patterns present in the EEG data that are characteristic of schizophrenia.

● While the LSTM model's performance shows the importance of considering the temporal dynamics of the signals; additionally, the relatively low accuracy of the LSTM model indicates that spectral information may not be as informative as temporal information in detecting schizophrenia.

● Overall, these findings demonstrate the potential of usage of CNN and its architectures for early detection of schizophrenia using EEG data and highlights the importance of considering both spectral and temporal information in such analyses. Future studies could consider using a combination of these models to improve detection accuracy further.

● In future work, it would be interesting to explore the combination model built with the cumulative architectural dependencies of the three models, tested in this paper. Moreover, metric evaluations can be implemented using different statistical analogies.


