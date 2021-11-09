FROM node:16.0.0

# Add the following line 
ENV CI=true

WORKDIR /app
COPY package.json ./
RUN npm install
COPY ./ ./
CMD ["npm", "start"]