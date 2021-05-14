From python:3

WORKDIR /usr/src/app

# Python dependencies
COPY requirements.txt ./
RUN pip install -r requirements.txt

COPY . .

CMD ["test.py"]
ENTRYPOINT ["python3"]
