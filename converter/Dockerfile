FROM tensorflow/tensorflow:1.5.0-py3

RUN apt update && apt install -y libsm6 libxext6 libxrender-dev

RUN pip install tfcoreml
RUN pip install coremltools
RUN pip install opencv-python
RUN pip install keras==2.1.3

EXPOSE 8888
