FROM nginx:stable

RUN rm /etc/nginx/conf.d/default.conf
COPY ./oro-commerce.conf /etc/nginx/conf.d/default.conf
WORKDIR /usr/share/nginx/html
