FROM nginx:alpine

RUN apk update && apk add bash
COPY ./config/nginx.conf /etc/nginx/nginx.conf
COPY ./config/proxy_params /etc/nginx/proxy_params
RUN mkdir /etc/nginx/modules-enabled \
	&& mkdir /etc/nginx/sites-enabled


