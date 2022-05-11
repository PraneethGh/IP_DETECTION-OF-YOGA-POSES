
# Detection of Yoga Poses using OpenPose and CNN

This work aims to estimate yoga poses from images. Initially pre-processing steps like smoothing, sharpening of image is done to remove different noises and maintain the quality of the image. OpenPose is used to detect joints from the human body. OpenPose is used to identify the joints in the image and is given as input to the prediction model. Deep learning model Convolutional Neural Network (CNN) is vastly used for classification of images. So, we have decided to use Densenet model, which is a variation of CNN, for classification. Comparative analysis of the outputs of the classification model, with and without OpenPose and with and without pre-processing filters have been recorded and inferences have been made and verified.


##  Dataset

- [Download Dataset](https://drive.google.com/drive/folders/19gRh8x21x0TG9RxSJ4VtxIlIUK8VI4OZ)
- [Source](https://www.kaggle.com/datasets/shrutisaxena/yoga-pose-image-classification-dataset)
## Demo

A runthrough and demo of the project is shown in this video.
- [Google Drive](https://drive.google.com/file/d/1bpMhshBIV8UUdLeyAPj8rNvycKoC27I9/view?usp=sharing)
- [Github](https://github.com/PraneethGh/IP_DETECTION-OF-YOGA-POSES/blob/main/CSE4019_PROJECT_DEMO.mp4)



## Requirements

### Software
- A web browser(Chrome, Firefox, etc.)
- A Google account
### Hardware


## Steps to Run

### Environment setup
- Download [dataset folder](https://drive.google.com/drive/folders/19gRh8x21x0TG9RxSJ4VtxIlIUK8VI4OZ) to your local system.
- Upload dataset to the base directory in [Google Drive](https://www.google.com/intl/en_in/drive/) storage of your google account.
- Upload the jupyter notebook containing the [code](https://github.com/PraneethGh/IP_DETECTION-OF-YOGA-POSES/blob/main/IP_J-Component_Code.ipynb) to [Google Colab](https://colab.research.google.com/?utm_source=scs-index) of your google account.
- In task bar of the opened colab notebook, click Runtime->Change runtime type->Hardware Accelarator to GPU.

### Execution
- Enter shortcut "Ctrl+F9" to  run entire code.
- To run specific cell, click on desired cell and enter "Ctrl+Enter".
## Output

### OpenPose
![OpenPose output 1]("https://github.com/PraneethGh/IP_DETECTION-OF-YOGA-POSES/blob/main/miscellaneous/OpenPose%20sample-2.jpeg")
![OpenPose output 2]("https://github.com/PraneethGh/IP_DETECTION-OF-YOGA-POSES/blob/main/miscellaneous/OpenPose%20sample-1.jpeg")
## Authors

- [Saravanan Kishan - 19BCE1337](https://github.com/kishan-ui)
- [S.M.Satya Sree Narayanan - 19BCE1172](https://github.com/satya8502)
- [Sanjit Kapoor - 19BCE1247](https://github.com/sanjitkapoor)
- [Praneeth Sethumadhavan - 19BCE1599](https://github.com/PraneethGh)


## References

- [OpenPose](https://github.com/CMU-Perceptual-Computing-Lab/openpose)