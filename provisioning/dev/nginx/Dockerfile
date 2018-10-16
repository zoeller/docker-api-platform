FROM nginx:1.15-alpine AS api_platform_nginx
MAINTAINER dev@zoeller.biz

COPY ./conf.d/default.conf /etc/nginx/conf.d/default.conf

WORKDIR /srv/api

#COPY --from=api_platform_php /srv/api/public public/