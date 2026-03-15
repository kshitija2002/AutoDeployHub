# Use Node.js official image
FROM node:18

# Set working directory inside container
WORKDIR /app

# Copy dependencies
COPY app/package*.json ./
RUN npm install

# Copy app code
COPY app/ ./

# Expose port
EXPOSE 3000

# Run app
CMD ["node", "app.js"]