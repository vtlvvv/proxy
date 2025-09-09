FROM nginx:stable-alpine
RUN apk add --no-cache nginx-mod-http-lua && mkdir -p /run/nginx
COPY nginx.conf /etc/nginx/nginx.conf
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
