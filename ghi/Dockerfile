FROM python:alpine

# Create app directory
WORKDIR /usr/src/app

# Bundle app source
COPY . .

EXPOSE 80
CMD [ "python3", "server.py" ]
