FROM alpine:latest
RUN apk add nodejs npm git
RUN git clone https://github.com/michaelkolesidis/zigzag.git && mv zigzag app
WORKDIR /app
EXPOSE 5173
RUN npm i
CMD ["npm", "run", "dev"]
