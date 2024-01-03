# Utiliza la imagen oficial de Nginx
FROM nginx:latest

# Copia el archivo de configuración de Nginx
COPY nginx.conf /etc/nginx/nginx.conf

# Exponer el puerto 80 para el servidor Nginx
EXPOSE 80

# Inicia Nginx en primer plano
CMD ["nginx", "-g", "daemon off;"]
