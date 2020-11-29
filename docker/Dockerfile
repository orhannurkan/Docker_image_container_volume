FROM python:3.8.6
RUN mkdir /app
COPY pipeline/model/model.py /app/model.py
COPY pipeline/preprocessing/preprocessing.py /app/preprocessing.py
COPY pipeline/utils/utils.py /app/utils.py
WORKDIR /app
CMD ["python", "model.py"]
