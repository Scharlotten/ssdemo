FROM python:3.12-slim

COPY requirements.txt /tmp/requirements.txt
COPY *.py /code/
RUN pip3 install -U -r /tmp/requirements.txt

EXPOSE 8501

#CMD ["streamlit", "run", "app.py"]

ENV PYTHONUNBUFFERED 1


