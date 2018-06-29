# node-lb-contacts:
# To build the container:
docker build --no-cache -t node-lb-contacts:latest .
# To run the container as a daemon:
docker run --name node-lb-contacts --rm -d -p 3000 node-lb-contacts
