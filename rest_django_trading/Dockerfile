FROM python:3
ENV PYTHONUNBUFFERED 1
RUN mkdir /rest_django_trading
WORKDIR /rest_django_trading
COPY requirements.txt /rest_django_trading/
RUN pip install -r requirements.txt
ADD . /rest_django_trading/

CMD python manage.py runserver 0.0.0.0:8100
