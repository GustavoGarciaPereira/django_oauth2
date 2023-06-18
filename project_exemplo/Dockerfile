# Pull base image
FROM python:3.10

ENV PYTHONUNBUFFERED 1

# Set work directory
RUN mkdir /app
WORKDIR /app

# Install dependencies
COPY requirements.txt /app/
RUN pip install -r requirements.txt

# Copy project
COPY . /app/
