## Train AI for Hand-to-Mouth Detection
### To detect hand-to-mouth eating using accelerometer and gyroscope data, using following general steps:
1. Collect Data: Collect accelerometer and gyroscope data while performing hand-to-mouth eating actions as well as other non-eating activities.
2. Preprocess Data: Normalize and segment the data into windows that can be fed into the model.
3. Feature Extraction: Extract relevant features from the raw sensor data.
4. Model Training: Choose a suitable machine learning or deep learning model and train it on the labeled data.
5. Model Evaluation: Evaluate the model's performance on a test set.
6. Deploy Model: Use the trained model to detect hand-to-mouth eating in real-time.
  
### For this task, Recurrent Neural Networks (RNNs) and their variants LSTM networks are a strong choice due to their ability to handle sequential data and capture temporal dependencies. 

### To see how it impletmented, Run the motion_sensor_data_lstm.ipynb in  [Github codespace](https://bookish-space-barnacle-q79vgx56ggq929p6w.github.dev/) or  [Google Colab](https://colab.research.google.com/)

To setup Github codespace install Python extension first, then run following command in terminal:\
```python3 -m pip install tensorflow[and-cuda]```

[Video for Training the Model](Hand_to_mouth_motion_detect_lstm-Model_Training.mp4)

[Video for Deployment](Hand_to_mouth_motion_detect_lstm-Deployment.mp4)
