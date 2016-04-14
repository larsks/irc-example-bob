FROM alpine

RUN apk add --update darkhttpd
COPY assets /assets
CMD ["darkhttpd", "/assets"]
