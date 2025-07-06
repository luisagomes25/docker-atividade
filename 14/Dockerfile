FROM ubuntu:22.04

# Evita prompts do apt
ENV DEBIAN_FRONTEND=noninteractive

# Atualiza e instala Python
RUN apt-get update && apt-get install -y python3

# Cria diretório de trabalho
WORKDIR /app

# Copia o script para o container
COPY process.py .

# Comando para rodar o script
CMD ["python3", "process.py"]

