# Use the official image as a parent image.
FROM python:3.8-buster

# Set the working directory.
WORKDIR /usr/src/app

# Copy the requirements file from your host to your current location.
COPY requirements.txt ./
# Install requirements
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

CMD [ "python", "api.py" ]