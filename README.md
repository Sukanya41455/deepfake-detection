# deepfake-detection

# Deepfake detection using Efficientnet

## BaseModel:

- Efficientnet-b0(Pretrained)

## Dataset :

- [Kaggle Deepfake Detection Challenge](https://www.kaggle.com/competitions/deepfake-detection-challenge/data)

## Parameters:

- Optimizer: Adam
- lr: 0.001
- Schedular: StepLR
- Epochs: 15
- Face Detector: MTCNN

## Important steps:

- Extract frames from videos
- Adjust imbalanced data
