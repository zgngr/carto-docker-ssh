# carto-docker-ssh

docker build -t sverhoeven/cartodb_ssh .
docker run -d -p 80:80 -p 2202:22 -h cartodb.localhost sverhoeven/cartodb_ssh
