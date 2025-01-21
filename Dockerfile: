# Use the official Python image
FROM python:3.9-slim

# Set the working directory
WORKDIR /app

# Copy the bot code and requirements
COPY angel.py /app/
COPY requirements.txt /app/

# Install dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Expose port 8080
EXPOSE 8080

# Start the bot
CMD ["python", "angel.py"]
