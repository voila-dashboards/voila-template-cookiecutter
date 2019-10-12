FROM python:3.7


RUN mkdir /home/voila
WORKDIR /home/voila

RUN pip install pipenv


COPY Pipfile Pipfile.lock ./
RUN pipenv install --dev
