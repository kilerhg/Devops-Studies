FROM python:3.10-alpine


COPY app /api/
COPY requirements.txt /api/

WORKDIR /api

RUN pip install --upgrade pip

RUN pip install -r requirements.txt

CMD ["uvicorn", "app:app", "--host", "0.0.0.0", "--port", "8000"]