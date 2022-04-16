# Bilibili-Videos-Download

For more detail, vist below link

https://pypi.org/project/bilili/

This tutorial assume that you are running Windows 10 and have installed Anaconda or miniconda

## Run below commands in Anaconda Prompt

conda create -n bilibili python=3.8 (bilili can run on python version equal or newer than 3.8.0)

conda activate bilibili

pip install bilili

## Make sure you have ffmpeg.exe in the bilibili environment under Scripts folder

Download ffmpeg for windows from 

https://ffmpeg.org/download.html

https://www.gyan.dev/ffmpeg/builds/

unzip the file and locate ffmpeg.exe in the bin folder

move ffmpeg.exe file to C:\Users\USER_NAME\anaconda3\envs\bilibili\Scripts

## Run below commands in Anaconda Prompt

bilili https://www.bilibili.com/video/BV1iY4y1e7pM
