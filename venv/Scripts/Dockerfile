FROM python:3.9

RUN pip install fastapi uvicorn pytest

#COPY requirements.txt .
#RUN pip install -r requirements.txt
#COPY app/requirements.txt .

COPY . /app
WORKDIR /app

CMD [ "python", "-m", "pytest" ]
