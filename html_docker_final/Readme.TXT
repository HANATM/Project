# Run docker in your machine, the run these commands in this directory:

docker build -t html-docker .
docker run -p 8080:80 -d html-docker

# You can acces the page via the link: http://localhost:8080/test/