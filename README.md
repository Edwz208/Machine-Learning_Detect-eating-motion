## Train AI for Hand-to-Mouth Detection
### Made to detect hand-to-mouth eating using accelerometer and gyroscope data, using the following general steps:
1. Collect Data: Collect accelerometer and gyroscope data while performing hand-to-mouth eating actions as well as other non-eating activities. For the training of data, 
2. Preprocess Data: Annotate the data, segmenting it into eating and non-eating. The program will automatically normalize such data.
5. The variant LSTM networks from Recurrent Neural Networks (RNNs) was used to train on the labeled data. 
6. Model Evaluation: The model's performance can be tested on a test set.
7. Deploy Model: Use the trained model to detect hand-to-mouth eating in real-time.

### To see how it impletmented, Run the motion_sensor_data_lstm.ipynb in  [Github codespace](https://bookish-space-barnacle-q79vgx56ggq929p6w.github.dev/) or  [Google Colab](https://colab.research.google.com/)

To setup Github codespace install Python extension first, then run following command in terminal:\
```python3 -m pip install tensorflow[and-cuda]```

[Video demonstrating training of model](Hand_to_mouth_motion_detect_lstm-Model_Training.mp4)

[Video demonstrating trained model detecting the hand to mouth motion from new data](Hand_to_mouth_motion_detect_lstm-Deployment.mp4)
