FROM nginx:alpine

# نسخ ملفات الموقع (السياق هو مجلد website/)
COPY . /usr/share/nginx/html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
