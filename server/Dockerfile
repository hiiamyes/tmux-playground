FROM python:latest
WORKDIR /app/
COPY . .
# RUN apt-get update && apt-get install -f vim
RUN pip install -r requirements.txt
EXPOSE 3030
CMD ["python", "src/server.py"]
