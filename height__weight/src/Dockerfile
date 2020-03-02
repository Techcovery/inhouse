FROM python:slim
COPY . /height_weight
WORKDIR /height_weight
RUN pip install -r requirements.txt
RUN python -m pip install  pickle-mixin
ENV http_port 9000
EXPOSE 9000
CMD python ./app.py
