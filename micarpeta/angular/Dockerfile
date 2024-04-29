# Usa una imagen de Nginx como base
FROM nginx:alpine

# Copia los archivos de la aplicación construida al directorio de Nginx
COPY ./dist/angular-nataliapilco /usr/share/nginx/html

# Expone el puerto 80 para que la aplicación Angular sea accesible
EXPOSE 80

# Comando para iniciar el servidor Nginx cuando se inicie el contenedor
CMD ["nginx", "-g", "daemon off;"]