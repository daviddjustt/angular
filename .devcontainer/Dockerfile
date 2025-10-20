# Use uma imagem base do Node.js
FROM mcr.microsoft.com/devcontainers/javascript-node:20-bookworm

# Instale dependências globais comuns (se necessário)
# Por exemplo, Angular CLI e Nest CLI
RUN npm install -g @angular/cli @nestjs/cli

# Opcional: Instale outras ferramentas que você possa precisar
# RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
#     && apt-get -y install --no-install-recommends git \
#     && apt-get clean -y && rm -rf /var/lib/apt/lists/*

# Defina o diretório de trabalho padrão
WORKDIR /workspace

# O usuário 'node' já está configurado na imagem base, o que é uma boa prática de segurança.
# Você pode adicionar comandos para configurar o ambiente do usuário 'node' se precisar.
