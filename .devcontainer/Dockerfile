FROM tensorflow/tensorflow:2.7.0-gpu
RUN rm -f /etc/apt/sources.list.d/cuda.list && rm -f /etc/apt/sources.list.d/nvidia-ml.list && apt-get update && apt-get install -y git
RUN python3 -m pip install --upgrade pip
RUN python3 -m pip install "deepvoxnet2[sitk]==2.14.0"
