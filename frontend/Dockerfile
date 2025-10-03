# frontend/Dockerfile
FROM nginx:1.27-alpine

# Bring your custom nginx.conf if you have one
COPY nginx.conf /etc/nginx/nginx.conf

# Static assets (index.html, main.js, css, etc)
COPY . /usr/share/nginx/html

EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
