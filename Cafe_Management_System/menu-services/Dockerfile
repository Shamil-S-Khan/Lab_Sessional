# Use official Node.js image
FROM node:18
# Set working directory
WORKDIR /app
# Copy package files and install dependencies
COPY package*.json ./
RUN npm install
# Copy the rest of the app
COPY . .
# Expose port (adjust if needed)
EXPOSE 3001
# Run the app
CMD ["npm", "start"]