FROM python:3.6.8
COPY getting_started.ini .
COPY producer.py .
RUN pip install confluent-kafka
CMD ["./producer.py", "getting_started.ini"]
