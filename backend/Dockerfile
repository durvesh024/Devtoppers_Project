FROM python:3.9.5
WORKDIR /app
COPY . .
RUN python -m pip install -r requirements.txt
ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1
EXPOSE 5000 
CMD [ "python", "app.py" ]