FROM node:10-alpine

# creamos un directorio de trabajo y nos posicionamos en el
WORKDIR /app

# copiamos los archivos necesarios al directorio actual
COPY package.json app.js ./

# Ejecutamos la instalación de componentes
RUN npm i

# Exponemos el puerto 3000
EXPOSE 3000

# Ejecutamos nuestra aplicación
CMD [ "node", "app.js" ]
