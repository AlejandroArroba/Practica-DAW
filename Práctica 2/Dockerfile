# Usa la imagen oficial de NGINX como base
FROM nginx:latest

# Copia los archivos estáticos al directorio de trabajo de NGINX
COPY index.html /usr/share/nginx/html/

# El puerto en el que NGINX escuchará
EXPOSE 80

# Comando para iniciar NGINX en primer plano
CMD ["nginx", "-g", "daemon off;"]
