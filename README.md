🚀 Começando

Aplicação simples construida utilizando Node, Docker e MongoDB

📋 Pré-requisitos
Node-Js
Docker
MongoDB

🔧 Instalação

Clone o Repositorio:

 '''bash
 git clone https://github.com/seu-user/web-server.git
 cd web-server
'''
Construa a imagem docker

'''bash
docker build -t web-server .
'''

Executar conteiner

'''bash
docker run -p 5000:5000 web-server
'''
Acessar a aplicação no endereço publicado 'https://localhost:5000' .

Para iniciar o Banco MongoDB, use o Docker-compose:

'''bash
docker-compose up -d 

⚙️ Pipeline

Cada vez que o codigo é enviado para a branch 'main', a pipeline:

1. Constroi a imagem Docker de pois executa testes basicos para verificar se a aplicação esta funcionando.

🛠️ Construído com
Docker
NodeJs
MongoDB


