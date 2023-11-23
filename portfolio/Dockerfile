FROM node:16

# Create app directory and copy source files
RUN mkdir -p /app
COPY . /app

WORKDIR /app

# Installing dependences
RUN npm install

# Building app
RUN npm run build

# Running the app
EXPOSE 8000

CMD ["npm", "run", "start"]