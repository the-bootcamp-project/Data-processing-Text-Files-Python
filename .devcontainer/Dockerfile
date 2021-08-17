FROM tbcp/datascience-python:latest

USER bootcamp

ENV PYTHONPATH "${PYTHONPATH}:/workspaces/Data processing Text-Files Python/"

WORKDIR /home/bootcamp/

COPY requirements.txt /home/bootcamp/
RUN pip3 install --upgrade -r /home/bootcamp/requirements.txt
