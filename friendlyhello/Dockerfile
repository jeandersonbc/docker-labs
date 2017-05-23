# Use an official Python runtime as a base image
FROM python:2.7-slim

# Sed the working directory to /app within the container
WORKDIR /app

# Copy the current directory into the container at /app
ADD . /app

# Install any needed packages specified in requirements.txt
RUN pip install -r requirements.txt

# Make port 80 available to the world outside this container
EXPOSE 80

# Define environment variable
ENV NAME World

# Run app.py when container launches
CMD ["python", "app.py"]
