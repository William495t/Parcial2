FROM python:3.10-slim

WORKDIR /app

ADD . /app

RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 8080

ENTRYPOINT ["python"]
CMD ["run.py"]