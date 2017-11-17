# Linear Regression demo 线性回归小示例
=======
# 线性回归示例说明
本示例是一个简单有趣的试验，是对天气变化的数据回归出一条预测线 出来，数据集非常简单，对应每一年二氧化碳的排放量，和每一年气温均值的变化，
编译环境是 jupyter notebook， 可以通过安装  Anaconda，导入 scikit-learn 库可以很容易实现，[github示例代码数据集](https://github.com/youngxiao/Linear-Regression-demo)，有人上传视频到
 [Youtube Video ](https://youtu.be/vOppzHpvTiQ?t=7m31s)，也可以看看。

## 概述
`linear_regression.ipynb`代码中主要分为两个部分
* 2D 线性回归作用于一个简单二维数据集 `challenge_dataset.txt` [X, Y]
* 3D 多元线性回归作用于气候变化数据集 `global_co2.csv` [Year, CO2 emissions, Global temperature].

Because of the small amount of data, and the random 10% of data chosen for testing, the scores have high variance.  

2D Linear Regression | 3D Multivariate Linear Regression 
:---: | :---: 
R<sup>2</sup> (Score):  0.651237006724 | R<sup>2</sup> (Score): 0.968933216107
![](https://github.com/ludobouan/linear-regression-sklearn/blob/master/data/2D_data.png) | ![](https://github.com/ludobouan/linear-regression-sklearn/blob/master/data/3D_data.png) 
![](https://github.com/ludobouan/linear-regression-sklearn/blob/master/data/2D_regression.png) | ![](https://github.com/ludobouan/linear-regression-sklearn/blob/master/data/3D_regression.png) 


## Usage
Run the jupyter notebook `linear_regression.ipynb`

##Challenge
> The challenge for this video is to use scikit-learn to create a line of best fit for the included 'challenge_dataset'. Then, make a prediction for an existing data point and see how close it matches up to the actual value. Print out the error you get. 

> Bonus points if you perform linear regression on a dataset with 3 different variables

## Dependencies
* matplotlib
* pandas
* numpy
* seaborn
>>>>>>> update
