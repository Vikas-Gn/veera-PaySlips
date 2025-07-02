# Use Node.js LTS
FROM node:18

# Set working directory
WORKDIR /app

# Copy package files and install
COPY package*.json ./
RUN npm install

# Copy the source
COPY . .

# Expose and start
EXPOSE 3069
CMD ["node", "server.js"]

