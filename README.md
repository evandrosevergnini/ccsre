# ccsre
Cloud Computing Deploy on Vercel
# Projeto de Aplicação Web com Python e Docker

Este projeto é uma aplicação web simples criada com Python e Docker. A aplicação utiliza o framework Flask para criar uma página web que exibe uma mensagem de boas-vindas.

## Tecnologias Utilizadas

* Python 3.9
* Flask 2.0.2
* Docker 20.10.7
* Vercel 12.0.0

## Como Executar o Projeto

Para executar o projeto, você precisará ter o Docker instalado em sua máquina. Em seguida, siga os passos abaixo:

1. Clone o repositório do projeto: `git clone https://github.com/usuario/projeto.git`
2. Acesse a pasta do projeto: `cd projeto`
3. Execute o comando para criar a imagem do Docker: `docker build -t projeto .`
4. Execute o comando para executar a imagem do Docker: `docker run -p 5000:5000 projeto`
5. Acesse a página web no navegador: `http://localhost:5000`

## Como Deployar o Projeto no Vercel

Para deployar o projeto no Vercel, você precisará ter uma conta no Vercel e ter configurado o repositório do projeto para deployar. Em seguida, siga os passos abaixo:

1. Acesse o site do Vercel e clique em "Criar um novo projeto"
2. Selecione a opção "Conectar repositório" e insira o endereço do seu repositório no GitHub
3. Selecione a branch do seu projeto que você deseja deployar
4. Configure as configurações do Vercel, como o nome do domínio, o nome do projeto e as configurações de segurança
5. Clique em "Criar um novo build" para criar um novo build do seu projeto
6. Verifique se o build do seu projeto foi criado com sucesso
7. Clique em "Deployar" para deployar o seu projeto no Vercel

## Contribuindo para o Projeto

Se você deseja contribuir para o projeto, por favor, siga os passos abaixo:

1. Clone o repositório do projeto: `git clone https://github.com/usuario/projeto.git`
2. Crie uma nova branch para o seu contributo: `git checkout -b nome-da-branch`
3. Faça as alterações necessárias no código do projeto
4. Adicione as alterações ao repositório: `git add .`
5. Comite as alterações: `git commit -m "Descrição das alterações"`
6. Envie as alterações para o repositório: `git push origin nome-da-branch`

## Licença

Este projeto é licenciado sob a licença MIT. Para mais informações, por favor, consulte o arquivo LICENSE no repositório do projeto.
