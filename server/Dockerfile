FROM python:3.8.1
ADD . /usr/src/app
WORKDIR /usr/src/app
EXPOSE 8080
RUN pip install --upgrade pip
RUN pip install -r requirements.txt
ENTRYPOINT ["python","index.py"]