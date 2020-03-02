FROM python:slim
COPY . /stock
WORKDIR /stock
RUN pip install -r requirements.txt
RUN python -m pip install  pickle-mixin
ENV http_port 8092
EXPOSE 8092
CMD python ./app.py
