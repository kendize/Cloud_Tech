FROM nginx:latest
COPY ./index.html /usr/share/nginx/html/index.html
WORKDIR /usr/share/nginx/html
RUN date +%x_%H:%M:%S:%N >> ./index.html