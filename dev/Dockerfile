# a basic nginx web server

# Pull base image.
FROM ubuntu

# Install Nginx.
RUN \
  apt-get update && \
  apt-get install -y nginx

# Define default command.
CMD ["nginx"]

# Expose ports.
EXPOSE 80
