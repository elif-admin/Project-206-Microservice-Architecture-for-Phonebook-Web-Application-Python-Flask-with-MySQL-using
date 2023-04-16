FROM python:alpine
COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt
COPY . /app
WORKDIR /app
EXPOSE 80
CMD python ./app.py