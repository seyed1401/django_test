# version 3.11.4 mined of python
FROM python:3.11.4-alpine

# is directory that i want to run myproject(this is an image of myproject)
WORKDIR /app



ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1
ENV PATH="/PY/BIN:$PATH"


# update pip
RUN pip install --upgrade pip


# copy req file in directory app(myproject)
COPY ./req.txt /app/req.txt
COPY . /app


# install all of packages that necessary for my app
RUN pip install -r req.txt



