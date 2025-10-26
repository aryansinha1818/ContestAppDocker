# Use Node.js for building
FROM node:18

WORKDIR /app

COPY package*.json ./
RUN npm install

COPY . .

# Expose frontend port
EXPOSE 5173

# Start frontend
CMD ["npm", "run", "dev", "--", "--host"]
