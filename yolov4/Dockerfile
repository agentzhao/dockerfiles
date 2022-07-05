FROM python:alpine

RUN apk update
RUN apk add git make automake gcc g++ subversion

RUN cd home && git clone https://github.com/kadirnar/yolov5-lite

RUN pip install --upgrade pip setuptools wheel

WORKDIR /home
