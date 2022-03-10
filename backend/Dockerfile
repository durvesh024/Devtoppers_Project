FROM python:3.9.5
WORKDIR /app
COPY . .
RUN pip install flask flask_cors pymongo
RUN pip install pyyaml
ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1
EXPOSE 5000 
CMD [ "python", "app.py" ]