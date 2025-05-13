FROM python:3.10-slim

WORKDIR /home/kth/docker/BasicServerClient/server

COPY requirements.txt .
RUN pip install -r requirements.txt

COPY main.py .

RUN chmod +x main.py

CMD ["fastapi", "run", "main.py"]
# ###
#
# 다음 주석을 지우고 docker 파일을 완성하자.
#
# ###