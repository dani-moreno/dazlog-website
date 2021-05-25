FROM nginx:latest

LABEL maintainer="<sistemas@nosolosoftware.es>"

# disabled cache for index.html
ADD https://gitlab.nosolosoftware.es/kubernetes/nginx/raw/master/default.conf /etc/nginx/conf.d/default.conf

ADD . /usr/share/nginx/html

CMD ["nginx", "-g", "daemon off;"]
