FROM python:3.8.5

WORKDIR /Course_Work_7/todolost
COPY requirements.txt .
RUN pip install -r requirements.txt
COPY  . ./
CMD python manage.py runserver 0.0.0.0:8000