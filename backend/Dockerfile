FROM python:3.11
ENV PYTHONUNBUFFERED=1
# ENV FLASK_APP=app.py
# WORKDIR /django
WORKDIR /backend

COPY requirements.txt requirements.txt
# RUN pip3 install -r requirements.txt
RUN pip install -r requirements.txt

COPY . .

# CMD ["python3","manage.py","runserver","0.0.0.0:8000"]
# CMD ["python3","app.py","runserver","0.0.0.0:8000"]
CMD ["python", "./app.py"] 

