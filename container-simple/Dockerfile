FROM ubuntu:latest

RUN apt-get update && apt-get upgrade -y
RUN apt-get install -y git python3 python3-pip --fix-missing

RUN pip install open-interpreter==0.2.4
RUN pip install numpy matplotlib pandas

WORKDIR /root
