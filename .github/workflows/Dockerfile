# Use Python official image
FROM python:3.9

# Set working directory
WORKDIR /app

# Copy app files
COPY app/ /app

# Install dependencies
RUN pip install flask

# Run the application
CMD ["python", "main.py"]
