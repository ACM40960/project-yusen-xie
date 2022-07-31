# Automatic License Number Plate Detection And Recognition
## _Table of Content_

- [_Automatic License Number Plate Detection And Recognition_]()
  - [_Background_](#background)
  - [_Install_](#install)
  - [_Usage_](#usage)
  - [_Example_](#example)
  - [_Performance_](#performance)
  - [_License_](#license)
 
## _Background_

> License plate recognition system (Vehicle License Plate Recognition) is an application of computer video image recognition technology in vehicle license plate recognition. Usually a license plate recognition system mainly includes the following four parts: vehicle image acquisition, license plate positioning, license plate character segmentation, license plate recognition Character recognition. This project is implemented through OpenCV and convolutional neural network(CNN).

## _Install_

> This project uses opencv and Pytorch. Go check them out if you don't have them locally installed.
```sh
pip install opencv-python==4.6.0.66
conda install pytorch torchvision torchaudio cpuonly -c pytorch
pip install imutils==0.5.4
pip install matplotlib==3.3.4
```
## _Usage_
> Firstly, CNN Model must be trained if there is no 'model.pkt'
```sh
python3 train.py
```
> Then, we can detect an image by input an image name
```sh
python3 Detect_Plate.py --target "the name of image"
```

## _Example_

```sh
python3 Detect_Plate.py --target images/Cars1.png
```

## _Performance_
![image](https://github.com/ACM40960/project-yusen-xie/blob/main/Figure_1.png)
![image](https://github.com/ACM40960/project-yusen-xie/blob/main/Figure_2.png)
![image](https://github.com/ACM40960/project-yusen-xie/blob/main/Figure_3.png)
![image](https://github.com/ACM40960/project-yusen-xie/blob/main/Figure_4.png)


## Conclusion
With the increasing number of vehicles, vehicle tracking has become an important research area for effective traffic control, surveillance and finding stolen vehicles. For this reason, efficient real-time license plate detection and recognition is very important for any country. License plate recognition is a huge challenge in developing countries due to variations in background and font colors, font styles, sizes, and non-standard characters of license plates. To overcome these problems, this study uses a deep learning strategy to improve the efficiency of license plate recognition. The collected images were captured under different lighting/contrast conditions, distance from the camera, and different rotation angles, and were verified to produce high recognition rates. The method helps law enforcement agencies and private organizations to use it effectively to improve homeland security. Future work may include training and validation of existing algorithms using a hybrid classifier approach, as well as improving the stability of license plate recognition systems under different weather conditions.

## Author
Yusen Xie , Ning Xu

## _License_
This Application is currently not licensed and is free to use by everyone.
