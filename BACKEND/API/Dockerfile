# Etapa base com Node.js
FROM node:18

# Diretório de trabalho dentro do container
WORKDIR /app

# Copia os arquivos do projeto para o container
COPY . .

# Instala as dependências
RUN npm install

# Expõe a porta usada pelo app
EXPOSE 3000

# Comando para iniciar o app
CMD ["npm", "start"]
