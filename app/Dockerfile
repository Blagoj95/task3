FROM python:3.6
EXPOSE 5000

WORKDIR /app

COPY . /app
RUN pip3 install --no-cache-dir -r requirements.txt


CMD python app.py