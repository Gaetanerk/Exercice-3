FROM python
WORKDIR /api/app
EXPOSE 5000
COPY ./app .
RUN pip install -r requirements.txt
RUN flask run --host=[0.0.0.0]