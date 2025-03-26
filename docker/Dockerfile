# Usa una imagen base de Node.js
FROM node:14

# Crea y establece el directorio de trabajo
WORKDIR /app

# Copia los archivos de la aplicación
COPY package*.json ./
RUN npm install
COPY . .

# Expone el puerto en el que la app se ejecutará
EXPOSE 3000

# Comando para iniciar el servidor
CMD ["node", "backend/server.js"]
