FROM node
WORKDIR /app

COPY ./nextjs-blog/pages ./pages
COPY ./nextjs-blog/package*.json .
COPY ./nextjs-blog/public ./public
COPY ./nextjs-blog/styles ./styles

RUN npm install
EXPOSE 3000
CMD ["npm","run","dev"]
