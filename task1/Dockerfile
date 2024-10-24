# the official Python image, version 3
FROM python:3

# Set the working directory inside the container
# All subsequent commands will be run in this directory
WORKDIR /src/app

# Copy the Python script 'cloud_usage.py' from the current directory
# to the working directory inside the container
COPY cloud_usage.py ./

# Install the 'requests' Python package, which is needed for HTTP requests
RUN pip install requests

# Define the default command to run the 'cloud_usage.py' script
# when the container starts
CMD ["python", "./cloud_usage.py"]
