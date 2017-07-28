# install log
*　参考了官方的install，还算顺利，因为之前 Anaconda 已经装好了，跑跑还可以


```
conda create -n tensorflow python=3.5
activate tensorflow
pip install --ignore-installed --upgrade https://storage.googleapis.com/tensorflow/windows/cpu/tensorflow-1.2.1-cp35-cp35m-win_amd64.whl
```
无显卡，选择了无GPU版本..