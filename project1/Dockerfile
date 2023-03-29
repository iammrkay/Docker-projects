FROM python:3-alpine3.15
WORKDIR /app
COPY . /app
RUN pip install --upgrade pip && pip install -r requirements.txt 
#RUN python3 ./index.py
CMD flask --app index run --host=0.0.0.0
EXPOSE 5000