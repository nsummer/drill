FROM python:2.7
LABEL maintainer="this is my first python docker"
RUN pip install flask
COPY app.py app/
WORKDIR app
EXPOSE 5000
CMD ["python", "app.py"]

