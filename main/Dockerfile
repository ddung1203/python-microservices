FROM python:3.10.6
ENV PYTHONUNBUFFERED 1
WORKDIR /app
COPY requirements.txt /app/requirements.txt
RUN pip install -r requirements.txt
COPY . /app

# EXPOSE 5000

CMD ["python", "consumer.py"]