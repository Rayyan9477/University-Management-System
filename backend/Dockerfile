FROM node:18-alpine

WORKDIR /app/server

# Copy package.json and package-lock.json
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the application
COPY . .


# Command to run the application
CMD ["node", "index.js"]