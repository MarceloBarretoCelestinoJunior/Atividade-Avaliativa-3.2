# Projeto BuscaCEP e Endereço

O projeto permite o usuário inserir um CEP para a busca de um endereço e armazenar os dados, e também permite o mesmo processo de forma reversa.

# Recursos utilizados no projeto

VSCode - Aplicação para edição de código e facilitar a visualização.
HTML e CSS - Estrutura e estilo da página.
JavaScript - Manipulação dos dados fornecidos pelo usuário e busca na API ViaCep.
API ViaCEP - API utilizada para a busca de CEP's e endereços.
Docker - Aplicação utilizada para a containerização do projeto.
Dockerfile - Definir a imagem (Nginx), copiar os arquivos para o container e configurar a porta.
Nginx - Servidor WEB utilizado para servir os arquivos do projeto (HTML, CSS e JavaScript).
Terminal - Utilizado para executar os comandos e interagir com o Docker.

# Como rodar o Projeto BuscaCEP e Endereço

1 - Faça o download dos arquivos do repositório.
2 - Faça o download do [Docker desktop](https://www.docker.com/products/docker-desktop/).
3 - Abra o terminal e navegue até o diretório do projeto.
4 - Execute o comando: "docker build -t busca-cep-nginx ." para construir a imagem Docker.
5 - Execute o comando: "docker run -d -p 80:80 busca-cep-nginx" para executar o container.
6 - Abra seu navegador web e digite localhost:80 para visualizar o projeto rodando.
