FROM jupyter/datascience-notebook:x86_64-ubuntu-22.04

USER root
RUN apt update
RUN pip install scanpy pybiomart combat inmoose
RUN apt install -y graphviz
RUN pip install seaborn --upgrade

USER correction
WORKDIR /home/correction
