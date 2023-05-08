# flask-docker

Simple docker image for python flask app

- To build this image
`$ docker build -t squidrings1/flask-docker:0.0.1.RELEASE .`

- To run image:
`$ docker container run -d -p 5000:5000 squidrings1/flask-docker:0.0.1.RELEASE`