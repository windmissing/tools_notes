# Failed to load the native TensorFlow runtime

## 问题现象

pip3 install tensorflow后import tensorflow时报以下错误：  
Failed to load the native TensorFlow runtime

tensorflow版本：2.3.1  
python版本:3.7

## 解决方法

安装Visual C ++ Redistributate 2015 x64，地址：
https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads

