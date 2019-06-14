FROM python:2.7
LABEL maintainer="this is my first python docker"
COPY app.py app/
WORKDIR app
RUN pip install flask redis
EXPOSE 5000
CMD ["python", "app.py"]

