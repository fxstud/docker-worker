FROM node:12

COPY package.json ./
WORKDIR /app
RUN npm install
COPY . .
EXPOSE 3000

CMD ['node','main']