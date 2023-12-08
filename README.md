# ELEN0016 Computer Vision Project: Detecting droplets and counting cells using OpenCV

## Table of Contents
- [Authors](#authors)
- [Introduction](#introduction)
- [Installation](#installation)

## Authors
- [Romain Lambermont](https://github.com/lambi702)  (romain.lambermont@student.uliege.be)
- [Arthur Louis](https://github.com/Opeka-2201)     (alouis@student.uliege.be)
- [Tom Navez](https://github.com/TomNavez)          (tom.navez@student.uliege.be)

## Introduction
This project is part of the ELEN0016 course at the Université de Liège. The goal of this project is to detect droplets and count cells in a given sequence. The project uses the OpenCV library to perform the image processing such as backgroung subtraction, thresholding, etc. The project is written in Python and can be run be simply lauching the Jupyter Notebook `main.ipynb` by correctly setting the different path variables to locate the data folders.

In the code, you will also find a notebook named `convnet.ipynb` that tried to solve the problem using a Convolutional Neural Network. We failed at that task but we decided to share the implementation we tried using [`geomloss`](https://www.kernel-operations.io/geomloss/) (uncommented draft).

## Installation
To install the project, simply clone the repository and install the required packages using the following command:
```bash
git clone https://github.com/lambi702/CV-Video_annotation.git
pip install -r requirements.txt
```

## Usage
To run the project, simply launch the Jupyter Notebook `main.ipynb` and set the different path variables to locate the data folders. The notebook will then run the different steps of the project and compute the results into a `.json` file and a `.tif` sequence.

## License
[MIT](https://choosealicense.com/licenses/mit/)
