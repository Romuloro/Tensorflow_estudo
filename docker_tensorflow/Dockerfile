#Imagem

FROM python:3.10.9-slim-buster

RUN mkdir -p /home/notebooks
WORKDIR /home/notebooks
COPY requirements.txt ./

RUN pip install --upgrade pip
RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 8888

ENTRYPOINT ["/bin/bash"]
