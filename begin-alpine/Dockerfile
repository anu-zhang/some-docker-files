# vi Dockerfile

FROM alpine:latest
MAINTAINER zhangmengke michael_u@163.com

# install nginx
RUN apk --update add nginx

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]