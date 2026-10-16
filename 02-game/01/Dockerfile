FROM alpine:latest
COPY ./app/ /app
RUN apk add nodejs npm
WORKDIR /app
EXPOSE 5173
RUN npm i
CMD ["npm", "run", "dev"]
