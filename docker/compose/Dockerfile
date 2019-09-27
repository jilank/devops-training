# Base Image
FROM ubuntu:16.04

# Owner (Optional)
MAINTAINER Jilan Kothakota

# Update Repo.
RUN apt-get update

# Install Apache
RUN apt-get install apache2 -y

# Copy html file
COPY info.html /var/www/html/

# Run Apache service
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
