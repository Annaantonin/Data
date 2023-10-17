# Data
in cmd
1. wsl -u root

docker pull tensorflow/tensorflow:latest-gpu-jupyter docker run -u $(id -u):$(id -g) -it --gpus all -p 8888:8888  tensorflow/tensorflow:latest-gpu-jupyter

in browser paste (copy from cmd smth like:  http://127.0.0.1:8888/tree?token=d073fd1579fc38c68febcd31e651a9e3ee700c002979b5a3 

in jupyter:
!git clone YOUR_REPO_WITH_YOUR_CODE


!git clone https://github.com/Crunch-UQ4MI/neuraluq.git
!pip install tensorflow-probability
!pip install scipy
import os
os.chdir("/tf/neuraluq/")
!python setup.py install

