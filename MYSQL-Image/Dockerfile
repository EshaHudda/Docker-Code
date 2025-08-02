# Start from the official MySQL 8.0 image
FROM mysql:8.0

# Optional: Add an initialization script
# This script will be run automatically when the container starts.
# Create a new directory for the script
RUN mkdir -p /docker-entrypoint-initdb.d

# Copy the SQL initialization script from your local machine into the container.
# Make sure you have a file named 'init.sql' in the same directory as your Dockerfile.
COPY init.sql /docker-entrypoint-initdb.d/
