# Projeto Docker Todo List

Este é um projeto que utiliza Docker para criar uma aplicação web de lista de tarefas (todo list).

O objetivo deste projeto é praticar os conceitos de Docker, como imagens, containers, volumes e redes. A aplicação web é composta por três serviços: um front-end em React, um back-end em Node.js e um banco de dados MongoDB. Cada serviço roda em um container separado e se comunica por meio de uma rede interna criada pelo Docker. Os dados da aplicação são persistidos em um volume que é montado no container do MongoDB.

## Funcionalidades

A aplicação web permite ao usuário:

- Criar um contêiner Docker para uma aplicação de front-end;
- Criar um contêiner Docker para uma aplicação de back-end;
- Criar um contêiner Docker para uma aplicação de testes;
- Orquestrar os três contêineres utilizando o Docker compose.

## Tecnologias utilizadas

As principais tecnologias utilizadas neste projeto são:

- Docker
- Docker-compose


## Instalação do projeto localmente

Para instalar e executar o projeto localmente, você precisa ter o Docker instalado na sua máquina. Depois, siga os seguintes passos:

1. Clone o repositório do GitHub:

```bash
git clone git@github.com:brenolg/Docker-To-Do-List.git

```

Construa as imagens dos serviços com os comandos no docker



## Requisitos do projeto

1. Crie um container em modo interativo, sem rodá-lo, nomeando-o como 01container e utilizando a imagem alpine na versão 3.12
2. Inicie o container 01container
3. Liste os containers filtrando pelo nome 01container
4. Execute o comando cat /etc/os-release no container 01container sem se acoplar a ele
5. Remova o container 01container
6. Faça o download da imagem nginx com a versão 1.21.3-alpine sem criar ou rodar um container
7. Rode um novo container com a imagem nginx com a versão 1.21.3-alpine em segundo plano nomeando-o como 02images e mapeando sua porta padrão de acesso para porta 3000 do sistema hospedeiro
8. Pare o container 02images que está em andamento
9. Gere uma build a partir do Dockerfile do back-end do todo-app nomeando a imagem para todobackend


## Agradecimentos
Este projeto foi desenvolvido como parte do curso de Desenvolvimento de Software da Trybe. Agradeço à Trybe pela oportunidade de aprender e praticar Docker e outras tecnologias.
