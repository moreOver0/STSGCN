FROM mxnet/python:1.5.0_gpu_cu100_py3

LABEL SongChao chaosong@bjtu.edu.cn

RUN apt-get update && apt-get install graphviz -y

RUN pip3 install pytest graphviz==0.8.4

WORKDIR /mxnet
