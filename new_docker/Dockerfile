FROM python:3.8-slim

WORKDIR /app

COPY . /app

RUN python -m pip install numpy simpy matplotlib scipy

ENV MPLBACKEND=Agg

CMD [ "python", "final_task2.py" ]

