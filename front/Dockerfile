# Utiliza la imagen oficial de Node.js 20
FROM node:20

# Establece el directorio de trabajo en /app
WORKDIR /app

# Copia los archivos de configuración de la aplicación
COPY package.json .

# Copia el resto de la aplicación
COPY . .

# Instala las dependencias
RUN npm install

# Construye la aplicación React
#RUN npm run build

# Exponer el puerto 3000 para el servidor de desarrollo de React
EXPOSE 3000

# Comando por defecto para iniciar la aplicación
CMD ["npm", "start"]
