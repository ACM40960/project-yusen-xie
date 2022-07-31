# Automatic License Number Plate Detection And Recognition
## _Table of Content_

- [_Automatic License Number Plate Detection And Recognition_]()
  - [_Background_](#background)
  - [_Tools_](#Tools)
  - [_Install_](#Install)
  - [_Download data_](#Downloaddata)
  - [_Usage_](#usage)
  - [_Example_](#example)
  - [_Performance_](#performance)
  - [_License_](#license)
 
## _Background_

> License plate recognition system (Vehicle License Plate Recognition) is an application of computer video image recognition technology in vehicle license plate recognition. Usually a license plate recognition system mainly includes the following four parts: vehicle image acquisition, license plate positioning, license plate character segmentation, license plate recognition Character recognition. This project is implemented through OpenCV and convolutional neural network(CNN).

## _Tools_
>You can compile them with any compiler that can edit .py files such as pycharm or jupyter.

## _Install_
####  Python version
>If your computer does not have the python component, first we need to download the installer from the Python website. https://www.python.org/downloads/
According to your operating system, on the web page, choose to download the latest version of the Python installer(note that python versions are updated frequently).
![image](https://github.com/ACM40960/project-yusen-xie/blob/main/Figure_5.png)

> This project uses opencv and Pytorch. 
>Go check them out if you don't have them locally installed.

>The following packages are installed via windows+cmd, enter the system, if it fails, please pip install --upgrade pip, if the installation fails and prompts for permission, please add --user, after pip install imutils, to achieve successful installation
```sh
pip install opencv-python==4.6.0.66
conda install pytorch torchvision torchaudio cpuonly -c pytorch
pip install imutils==0.5.4
pip install matplotlib==3.3.4
```
## _Download data_
>For any program, after we have installed the necessary components, it's time to prepare the data
>The data has been uploaded to my Google Drive, and I have uploaded a copy on github.

>Here is the Link to Google Drive:https://drive.google.com/drive/folders/1Grli6Q_1cK0o39csBhfXTU10vbNV-PnB?usp=sharing

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

## Author
Yusen Xie , Ning Xu

## _License_
This Application is currently not licensed and is free to use by everyone.
