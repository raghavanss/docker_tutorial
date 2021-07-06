FROM ubuntu

RUN apt-get -y update

RUN mkdir -p /opt/app/flask_container_tutorial
RUN apt install -y python3-pip

COPY requirements.txt /opt/app/flask_container_tutorial

COPY pip.conf /etc/
COPY . /opt/app/flask_container_tutorial

WORKDIR /opt/app/flask_container_tutorial
RUN pip install -r requirements.txt

CMD python3 app.py