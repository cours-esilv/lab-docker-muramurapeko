FROM python:3.12

WORKDIR /app

# COPY requirements.txt .

RUN pip install -r requirements.txt

COPY . .

CMD [ "python", "app.py" ]

CMD python3 -m flask run --host=0.0.0.0
