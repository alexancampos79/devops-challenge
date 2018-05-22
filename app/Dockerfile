FROM python:3.6-alpine
WORKDIR /web
RUN mkdir -p /web
ADD requirements.txt /web/
ADD app.py /web/
RUN pip install -r requirements.txt
ADD . /web
ENTRYPOINT ["python"]
CMD ["app.py"]

