FROM python:3.11-bullseye

COPY ./requirements.txt .

RUN pip install -r requirements.txt

WORKDIR /notebooks

CMD ["jupyter", "lab", "--ip", "0.0.0.0", "--port", "8888", "--NotebookApp.token=''", "--NotebookApp.password=''", "--no-browser", "--allow-root"]