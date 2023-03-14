# wine label reader toolkit

The goal here is to train the computer to read a bottle of wine's label from a simple photo using tensorflow, OpenCV and Tesseract.

To use this package on your machine you have to install the dependencies in the requirement.txt move the photo you want to train in the "X" folder and the masks in the "y" folder and the photo you want to read in the "to_read" folder.
To configure the files location or the parameters of the U-net use the Config.json file.

## train model on images
```
python main.py --train
```
## read images
```
python main.py --read
```
## train then read images
```
python main.py --train --read
```