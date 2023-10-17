# Use base image
FROM mcr.microsoft.com/devcontainers/base:jammy

# Update and upgrade system
RUN apt-get update && apt-get upgrade -y

# Install Python and pip
RUN apt-get install -y python3 python-is-python3 python3-pip

# Install requirements.txt
COPY requirements.txt .
RUN pip3 install -r requirements.txt
