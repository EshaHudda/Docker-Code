# Base image with desired node version
FROM node:16

# Create a working directory to copy the source code from host to container
WORKDIR /node

# Copy the source code intto the container
COPY . .

# Install the required nodejs packages
RUN npm install

# To execute all the commands which are required to run the node application
CMD ["node","app.js"]