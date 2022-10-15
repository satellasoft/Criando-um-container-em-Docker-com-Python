# Criando um container em Docker com Python

Esse repositório faz parte do nosso artigo oficial sobre Pyhton e Docker. Aqui criamos uma simples imagem para executar um arquivo Python.

Artigo oficial: https://satellasoft.com/artigo/python/criando-um-container-em-docker-com-python

Imagem oficial do Python: https://hub.docker.com/_/python

## Organizando o projeto

- 1 - Crie uma pasta chamada **app** na raiz;
- 2 - Crie um arquivo chamado **Dockerfile**;
- 3 - Crie um arquivo chamado **.dockerignore**. Inclua nele os caminho e arquivos que não devem estar no container.

## Criando o script

- 1 - Dentro da pasta /app, crie um arquivo chamado **index.py**;
- 2 - No arquivo criado, inclua o comando ```print("SatellaSoft tutorial")```.

## Criando o container

1 - Abra o terminal na pasta raiz do projeto e execute o comando```docker build -t micro-python .```;
2 - Para rodar o container, execute o comando ```docker run -it micro-python```.