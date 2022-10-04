FROM nginx:latest
RUN useradd 1001
RUN mkdir /app
COPY index.html /app/
COPY nginx.conf /etc/nginx/
COPY default.conf /etc/nginx/conf.d/
