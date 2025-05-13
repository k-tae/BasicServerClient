FROM python:3.10-slim

WORKDIR /home/ljb/BasicServerClient/client

COPY requirements.txt .

RUN pip install -r requirements.txt

COPY run_client.py .

RUN chmod +x run_client.py

CMD [ "python", "run_client.py" ]