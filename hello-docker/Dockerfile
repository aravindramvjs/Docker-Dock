# 1. Define the operating system. Here which Node which is build top of alpine linux distros
FROM node:alpine 
# 2. Copy our files and put into the filesystem of the Docker image being built.
COPY . /app
# 3. Mention the working dir. Here which is /app
WORKDIR /app
# 4. Run the application
CMD node app.js