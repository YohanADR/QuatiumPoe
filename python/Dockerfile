FROM selenium/standalone-chrome:112.0

COPY ../env/ . 

WORKDIR /app

COPY requirements.txt .

RUN pip install --no-cache-dir -r requirements.txt

COPY . .

CMD ["python", "main.py"]