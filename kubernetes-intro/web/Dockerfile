FROM nginx
COPY nginx/nginx.conf /etc/nginx/conf.d/default.conf
COPY app /usr/share/nginx/app

RUN chown -R 1001 /var/cache/nginx && \
    chown -R 1001 /var/log/nginx && \
    chown -R 1001 /etc/nginx/conf.d && \
    chown -R 1001 /usr/share/nginx

RUN touch /var/run/nginx.pid && \
    chown -R 1001 /var/run/nginx.pid

USER 1001