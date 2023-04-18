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