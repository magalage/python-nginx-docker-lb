FROM python:3
COPY ./requirements.txt /requirements.txt
WORKDIR /
RUN pip install -r requirements.txt
COPY . /
CMD [ "app1.py" ]
ENTRYPOINT [ "python3" ]