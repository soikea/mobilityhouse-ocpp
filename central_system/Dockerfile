FROM python:3.8

# Install zsh
RUN apt-get update
RUN apt-get install zsh -y

WORKDIR /mobilityhouse-ocpp-central-system
COPY ./ ./

RUN pip install .
RUN pip install websockets