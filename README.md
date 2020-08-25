# Lokari - Web server log anomaly detector 
### Machine learning based monitoring application for anomalies in web server logs.

Machine learning project by Tuomo Kuure [(tqre)](tqre.wordpress.com) and Joni Hakala [(Dunttus)](dunttus.com).  
Supervising teacher: [Tero Karvinen](http://terokarvinen.com) - [Haaga-Helia University of Applied Sciences](http://www.haaga-helia.fi/en/frontpage)  

Original project blog: https://ailogs.design.blog/ \
This repository is a cleaned version of the original: https://github.com/Dunttus/AI-Project

### Directories:
**/.idea** - PyCharm configuration files \
**/autoencoder** - Autoencoding ML layer construction \
**/data_processing** - Data processing modules \
**/datasets** - Datasets used in training \
**/docker** - Project runtime container

### Files:
**config.py** - Main configuration file \
**main.py** - Log monitor \
**train.py** - Detector training

### Requirements
* Python 3.6.9
* Tensorflow 2.1.0 plus a few other libraries
* Linux with Apache/Nginx web server
* NVIDIA GPU Support with Docker 19.03
  + tensorflow/tensorflow:latest-gpu-py3 (see our Dockerfile)
  + nvidia-container-toolkit
  + nvidia-container-runtime

