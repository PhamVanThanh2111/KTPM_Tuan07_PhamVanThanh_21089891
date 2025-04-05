# Base image
FROM node:18-alpine

# Tạo thư mục app
WORKDIR /app

# Copy package.json và package-lock.json
COPY package*.json ./

# Cài đặt dependencies
RUN npm install

# Copy source code
COPY . .

# Expose port
EXPOSE 3000

# Command để chạy ứng dụng
CMD ["npm", "start"]