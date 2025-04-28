# Use the official Node.js 18 image
FROM node:18

# Set the working directory inside the container
WORKDIR /app

# Copy package.json and package-lock.json first
COPY package*.json ./

# Install project dependencies
RUN npm install

# Copy the rest of your application files
COPY . .

# Expose port 80 to the outside
EXPOSE 80

# Command to run the app
CMD ["npm", "start"]
