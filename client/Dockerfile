FROM node:alpine
# fix cra for docker
ENV CI=true

WORKDIR /app
COPY package.json ./
RUN npm install
COPY ./ ./


CMD ["npm", "start"]