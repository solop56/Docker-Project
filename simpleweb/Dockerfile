# Specify the base Image
FROM node:alpine

# Set a clean working directory
WORKDIR /app

# Install some dependencies
COPY ./ ./
RUN npm install

# Default command
CMD ["npm", "start"]