# Use a lightweight Python image
FROM python:3.9-slim

# Set the working directory in the container
WORKDIR /app

# Copy the HTML file into the container
COPY index.html /app/

# Copy the Python server script into the container
COPY server.py /app/

# Expose port 8080
EXPOSE 8080

# Run the Python server when the container starts
CMD ["python", "server.py"]
