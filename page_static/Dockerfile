FROM nginx:1.14-alpine

WORKDIR /usr/share/nginx/html

COPY . .

## Copy our default nginx config
COPY nginx/default.conf /etc/nginx/conf.d/

CMD ["nginx", "-g", "daemon off;"]