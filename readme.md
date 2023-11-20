# Project Name

This model is a bottle can classifier that helps tell you whether you are looking at a bottle or a can.  This classifer could be used in real life when you need to throw something away, but you don't know whether to throw it in a bottle receptacle or a can receptacle, which would help with items getting put in the wrong bins.

![image](https://drive.google.com/uc?export=view&id=1-neSOMjQmyGkxSJAThSoXqOHt6m8vZCN)



## The Algorithm
 This model was made using the Jetson Nano.  This model is a Resnet18 model that runs on imagenet.py whose dataset includes pictures of bottles and cans.  When the model is ran you get the percentage of how much the model believes it is a bottle or a can.

## Running this project

1. download the model and the images that you want and put them in the model and data directories
2. get into the jetson inference library (if you don't have it download it)
3. change directories using ``` cd jetson-inference/python/training/classification ```

[View a video explanation here](video link)
