FROM python:3.6.8
COPY getting_started.ini .
COPY consumer.py .
RUN pip install confluent-kafka
CMD ["./consumer.py", "getting_started.ini"]
