#Base Image
FROM python:2.7-slim

#WORKING Dir.
WORKDIR /usr/src/app

# Req Files
ADD .  /usr/src/app


# Flask Package Installation
RUN pip install --trusted-host pypi.python.org -r req.txt

# Expose my App. 
EXPOSE 8081

CMD [ "python", "app.py" ]
