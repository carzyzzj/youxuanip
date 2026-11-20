FROM node:20-alpine

WORKDIR /app

RUN apk add --no-cache git

RUN git clone https://github.com/uxiaohan/CloudflareIP-dnspod-ddns.git .
RUN npm install

CMD ["npm", "run", "dev"]
