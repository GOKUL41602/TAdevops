FROM node:alpine

WORKDIR /app

# Installing dependencies

RUN npm cache clean --force
#RUN npm install
#
RUN npm install express

# Copying all the files in our project
COPY . .

EXPOSE 3000

# Starting our application
CMD ["node","app.js"]
