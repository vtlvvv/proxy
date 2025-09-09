FROM nginx:stable-alpine

# Install nginx Lua module
RUN apk add --no-cache nginx-mod-http-lua

COPY nginx.conf /etc/nginx/nginx.conf
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
