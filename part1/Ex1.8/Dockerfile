FROM ubuntu:20.04

# Install curl
RUN apt-get update && apt-get install -y curl;

# Command to copy file script into our image and run on container starting
CMD echo "Input website:"; read website; echo "Searching..."; sleep 1; curl http://$website;