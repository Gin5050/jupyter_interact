FROM nvcr.io/nvidia/pytorch:19.08-py3

RUN apt-get clean && apt-get update

RUN pip install msgpack==0.5.6
RUN pip install pillow tensorboard matplotlib tensorflow future torch torchvision jupyter --ignore-installed
RUN pip install wrapt==1.10.0 --ignore-installed

WORKDIR /workspace/work

CMD /bin/bash