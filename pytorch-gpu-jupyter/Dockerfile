FROM pytorch/pytorch:1.13.0-cuda11.6-cudnn8-runtime

RUN apt update 
RUN apt install -y wget nano git

EXPOSE 8888

RUN conda install -c conda-forge jupyterlab
RUN pip install tensorboard
RUN conda install torchaudio
RUN conda install torchvision


CMD ["bash"]