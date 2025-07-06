FROM node:18-alpine

WORKDIR /app

# Instala o git dentro do container
RUN apk add --no-cache git

# Clona o repositório direto do GitHub
RUN git clone https://github.com/eMahtab/node-express-hello-world .

# Instala dependências do projeto
RUN npm install

# Expõe a porta que a aplicação usa
EXPOSE 3000

# Comando para iniciar o servidor
CMD ["npm", "start"]

