# docker-wordpress
AVALIAÇÃO FINAL N3 - REDES 

Grupo: ALYSON DE LIMA DE OLIVEIRA, Jeliel Nunes, Thiago Fernando Sanson de Souza

  Como funciona ?
   Como instalar e testar o sistema

 Como funciona ? basta seguir estes passos:
 
   1. Pré-requisitos

- Ter o Docker instalado  
- Ter o Docker Compose (integrado ao Docker Desktop ou standalone)  

Verifique com:

docker --version
docker compose version

2. Clone o repositório

No terminal:
```bash
git clone https://github.com/ThiagoFSDS/docker-wordpress.git
cd docker-wordpress

 3. Inicie os containers

Dentro da pasta do projeto:

docker compose up -d

Isso vai baixar as imagens e subir quatro containers:
- NGINX (proxy reverso)  
- MySQL 5.7 (banco de dados)  
- WordPress  
- phpMyAdmin  

Aguarde 30 segundos para tudo ficar pronto.



 4. Complete a instalação do WordPress

1. Acesse no navegador:  
  
   http://localhost/botafogodefuteboleregatas/wp-admin
  
2. Escolha o idioma  
3. Crie um usuário e senha de administrador  
4. Configure título do site e finalize o assistente  

Após isso, o front-end estará disponível em:

http://localhost/botafogodefuteboleregatas



 5. Acesse o phpMyAdmin (opcional)

Se quiser ver ou editar diretamente o banco de dados:

http://localhost:8080

- Usuário: root  
- Senha: rootpass  


 6. Parar e remover containers

Quando terminar de testar:

docker compose down

E é isso pe..pe..pessoal

Fé no pai que isso vai rodar com vocês também 
