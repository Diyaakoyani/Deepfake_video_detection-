This project utilizes a subset of the DeepFake Detection Challenge Dataset from Kaggle, which contains a large collection of videos and audio files altered using deepfake techniques.
🔗 Dataset Link: https://www.kaggle.com/competitions/deepfake-detection-challenge/data

Training Data: 400 .mp4 videos labeled as either real or fake
Testing Data: 400 .mp4 videos used to evaluate model performance
Metadata Description:

filename – Name of the video file
label – Ground truth: 1 for FAKE, 0 for REAL
original – If the video is FAKE, this field indicates the name of the original REAL video
split – Indicates the dataset split (value is always "train" in this sample)
This dataset served as the foundation for training and testing our deepfake detection model.