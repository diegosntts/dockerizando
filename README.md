# Dockerizei App Node.js

Este repositório contém um aplicativo Node.js dockerizado, o que simplifica a implantação e execução em diferentes ambientes.

## Como Usar

Certifique-se de ter o Docker instalado em seu sistema. Em seguida, siga estas etapas:

1. Clone este repositório:

   ```bash
   git clone https://github.com/diegosntts/dockerizando.git
   
2. Navegue até a pasta do projeto:
   
   ```bash
   cd dockerizando
   
4. Construa a imagem Docker:

   ```bash
   docker build -t nome-da-imagem .
   
6. Execute o contêiner:

   ```bash
   docker run -p 3000:3000 -d nome-da-imagem
