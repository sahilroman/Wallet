FROM python:3.8-slim-buster

WORKDIR /Users/lovet/waller/project

COPY requirments.txt requirments.txt
RUN python -m pip install --upgrade pip
RUN pip install -r requirments.txt

COPY . .

CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]