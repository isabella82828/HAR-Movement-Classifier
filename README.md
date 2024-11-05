# HAR-Movement-Classifier
## Overview 
Human Activity Recognition (HAR) involves identifying a person’s physical activities through sensor data. In this project, we use the HAR dataset collected from smartphone accelerometer and gyroscope readings. The data is labeled with six types of activities, and our goal is to train an LSTM-based neural network to classify these movements accurately:

- Walking
- Walking upstairs
- Walking downstairs
- Sitting
- Standing
- Laying down
  
Unlike classical machine learning approaches that rely heavily on signal processing and extensive feature engineering, LSTMs allow us to feed raw or minimally preprocessed data directly into the network, which then learns the underlying patterns autonomously.

## Dataset 
The Human Activity Recognition Using Smartphones dataset consists of accelerometer and gyroscope data from smartphones worn on the waists of 30 subjects. Each subject performed six activities under similar experimental conditions. The dataset is structured in a way that allows for sequential learning, which makes it a perfect candidate for LSTM networks.

## Requirements 
- Python 3.6+
- TensorFlow 2.x
- Numpy
- Pandas
- Scikit-learn (for data preprocessing)
- Matplotlib (for plotting results)

# Future Improvements 
1. Hybrid Architectures: Combine CNNs with LSTMs to capture spatial and temporal features to improve recognition accuracy.

2. Attention Mechanisms: Integrate attention layers to enable the model to focus on relevant parts of the input sequence, enhancing distinction between similar activities.

3. Transfer Learning: Pre-train the model on related datasets before fine-tuning on HAR data to boost performance, especially with limited labeled data.

4. Real-Time Processing: Optimize the model for real-time inference, enabling deployment in applications requiring immediate activity recognition.

