The DockerfileAuth needs to be run to create the authserver image
(you can also edit the Dockerfile)
To create the images run
docker build -t jrwtango/books .
docker build -f DockerfileAuth -t jrwtango/authserver .
