FROM jupyter/scipy-notebook

USER root
RUN apt-get update 
RUN apt-get install -y graphviz

COPY requirements.txt .
RUN pip3 install -r requirements.txt