### 安装教程
https://www.tensorflow.org/install/pip?hl=zh-cn#macos
```
brew update
brew install python
python3 -m venv --system-site-packages ./venv
source ./venv/bin/activate 
pip install --upgrade pip
pip list

pip install --upgrade tensorflow

python -c "import tensorflow as tf;print(tf.reduce_sum(tf.random.normal([1000, 1000])))"
```


### MACOS版本管理
>tensorflow对python的版本还是有一定的要求，如果不匹配的话需要使用pyenv进行管理
https://juejin.cn/post/6976890953009201159


### 安装
首先确保已经安装python，然后用pip来安装matplotlib模块。
进入到cmd窗口下，建议执行python -m pip install -U pip setuptools进行升级。
接着键入 python -m pip install matplotlib 进行自动的安装，系统会自动下载安装包

### 课程源码


#### 课程2
https://colab.research.google.com/github/lmoroney/mlday-tokyo/blob/master/Lab2-Computer-Vision.ipynb#scrollTo=MMckVntcSPvo

错误解决：https://github.com/tensorflow/tensorflow/issues/33285
#### 课程3
https://colab.research.google.com/github/lmoroney/mlday-tokyo/blob/master/Lab3-What-Are-Convolutions.ipynb#scrollTo=7oPhUPNhuGWC


#### 课程4
https://colab.research.google.com/github/lmoroney/mlday-tokyo/blob/master/Lab4-Using-Convolutions.ipynb

练习：https://colab.research.google.com/github/lmoroney/dlaicourse/blob/master/Exercises/Exercise%203%20-%20Convolutions/Exercise%203%20-%20Question.ipynb

#### 课程5
https://colab.research.google.com/github/lmoroney/mlday-tokyo/blob/master/Lab5-Using-Convolutions-With-Complex-Images.ipynb


#### 课程6
https://colab.research.google.com/github/lmoroney/mlday-tokyo/blob/master/Lab6-Cats-v-Dogs.ipynb

https://colab.research.google.com/github/lmoroney/mlday-tokyo/blob/master/Lab6-Cats-v-Dogs.ipynb

