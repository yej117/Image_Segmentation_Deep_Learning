# Image Segmentation Deep Learning 

This respository is used as the final project for the course "Deep Learning" on [opencampus](https://edu.opencampus.sh/) in the Winter semester 2020/21.

This project managed to finish the task of image segmentation of the Kaggle Challenge: [Carvana Image Masking Challenge](https://www.kaggle.com/c/carvana-image-masking-challenge/overview)<br>
*See some example notebooks using UNet:* [Link 1](https://www.kaggle.com/hotuanlong/u-net/notebook), [Link 2](https://www.kaggle.com/gargkaman7/semantic-segemntation), [Link 3](https://www.kaggle.com/uysimty/carvana-image-masking#Model)


## Dataset
- Google Drive: right click the shared folder and click on "Add a shortcut to Drive" to make sure you can easily reach the folder
- Instruction for loading data in Google drive to Google Colab
```
from google.colab import drive
drive.mount('/content/drive')
%cd /content/drive/MyDrive/DL_project/kaggle/data/
```

## Background Knowledge for Image Segmentation
* [Introduction to Image Segmentation](https://www.analyticsvidhya.com/blog/2019/04/introduction-image-segmentation-techniques-python/)

## Possible datasets
**For all: It's interesting to look through the datasets listed down, and please feel free to add what you've searched**
1. Some challenges on Kaggle:
    - [38-Cloud: Cloud Segmentation in Satellite Images](https://www.kaggle.com/sorour/38cloud-cloud-segmentation-in-satellite-images)
    - [95-Cloud: Cloud Segmentation on Satellite Images](https://www.kaggle.com/sorour/95cloud-cloud-segmentation-on-satellite-images/version/1)
    - [Ships in Satellite Imagery](https://www.kaggle.com/rhammell/ships-in-satellite-imagery)
    - [Understanding Clouds from Satellite Images](https://www.kaggle.com/c/understanding_cloud_organization) 
    - [Carvana Image Masking Challenge](https://www.kaggle.com/c/carvana-image-masking-challenge/overview)
2. The [GitHub Repository](https://github.com/chrieke/awesome-satellite-imagery-datasets) collecting some satellite imagery datasets: 
3. [Image Segmentation tutorial](https://www.tensorflow.org/tutorials/images/segmentation) with [Oxford-IIIT Pet Dataset](https://www.robots.ox.ac.uk/%7Evgg/data/pets/)
4. Open Images 2019 - [Instance Segmentation](https://www.kaggle.com/c/open-images-2019-instance-segmentation/data)
5. [Segmentation evaluation database](http://www.wisdom.weizmann.ac.il/~vision/Seg_Evaluation_DB/index.html)
6. [A Large-scale Dataset for Instance Segmentation in Aerial Images](https://captain-whu.github.io/iSAID/dataset.html)

## Possible Algorithms
* [Background Paper about FractalNet](https://arxiv.org/pdf/1605.07648.pdf)
* [A repository for Deep Segmentation with several CNNs for semantic segmentation (U-Net, SegNet, ResNet, FractalNet) using Keras](https://github.com/danielelic/deep-segmentation/blob/master/train_fractal_unet.py)
* [A Repository for FractalNet implementation in Keras](https://github.com/snf/keras-fractalnet/blob/master/src/fractalnet.py)
* [Introduction about U-Net](https://neurohive.io/en/popular-networks/u-net/)
* [Origin paper for U-Net](https://arxiv.org/abs/1505.04597)


## Notes for some possible further applications
* [Optical flow](https://nanonets.com/blog/optical-flow/)
* [Using Machine Learning to “Nowcast” Precipitation in High Resolution](https://ai.googleblog.com/2020/01/using-machine-learning-to-nowcast.html)
* [A Neural Weather Model for Eight-Hour Precipitation Forecasting](https://ai.googleblog.com/2020/03/a-neural-weather-model-for-eight-hour.html)


## Others 
Simple guide for anyone who is not familiar with markdown file: [markdown cheatsheet](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)

## Notebook examples to work from
https://github.com/yej117/Cloud_Segmentation_Deep_Learning/blob/main/DL_Images.ipynb


## Presentation of the final project
Date: 18th Jan. 2021
Time: 10 minutes for presentation + 5 minutes for a round of questions

Presentation structure:
- [x] Group: who are inside the group
- [x] Project: short description of the project and the motivation behind
- [x] Tools (optional)
- [x] Architecture
- [x] Story (optional): attempts, failures, successes
- [x] Results 
- [ ] Baselines - how to measure the performance 
- [ ] Missing (optional) - is there something you missed to improve in the project?
- [x] Future work (optional) - how to improve

Sharing (optional) on the opencampus gitbook: Code, Data and Presentation

