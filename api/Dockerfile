FROM python
WORKDIR /app
EXPOSE 5000
COPY ./app /app
RUN pip install -r requirements.txt && flask run --host=[0.0.0.0]