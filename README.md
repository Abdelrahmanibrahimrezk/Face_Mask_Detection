# Face_Mask_Detection

<!-- ABOUT THE PROJECT -->
## About The Project

Face Mask Detection System built with OpenCV, Keras/TensorFlow using Deep Learning and Computer Vision

![Output](https://user-images.githubusercontent.com/89320483/158674984-9135e1eb-7df1-44dc-a9fa-780427fcb268.jpg)


I used the MobileNetV2 to detect if the person wearing a Mask or not and then use dnn in Opencv to detect faces

## Getting Started

### Kaggle Dataset
First of all, we will import the dataset from Kaggle
  ```sh
  ! mkdir ~/.kaggle

  ! cp kaggle.json ~/.kaggle/

  ! chmod 600 ~/.kaggle/kaggle.json

  !kaggle datasets download -d ashishjangra27/face-mask-12k-images-dataset

  !unzip face-mask-12k-images-dataset.zip
  ```
### Training

  ```sh
  !python train_mask_detector.py --dataset "Face Mask Dataset"
  ```
### Training/Validation

![training_plot](https://user-images.githubusercontent.com/89320483/158676376-1ba6c4c3-df77-4d81-a961-582b93a4452c.png)

### Detect

  ```sh
  !python detect_mask_image_py.py --image 0.png
  ```
