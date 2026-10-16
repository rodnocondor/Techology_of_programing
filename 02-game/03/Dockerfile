FROM alpine:latest
EXPOSE 5173
COPY ./install.sh /install.sh
RUN chmod +x /install.sh
CMD ["ash", "./install.sh"]
