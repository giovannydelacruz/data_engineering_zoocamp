FROM python:3.9

RUN pip install --upgrade pip && \
    pip install numpy && \
    pip install pandas

WORKDIR /app

COPY . .

ENTRYPOINT [ "python", "pipeline.py" ]