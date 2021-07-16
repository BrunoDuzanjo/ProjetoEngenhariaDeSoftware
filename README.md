# Projeto Final de Engenharia De Software
## IFCE - P7 de Informática
## Professor: Cesar Olavo de Moura Filho

# Equipe:
### Bruno Silveira, Guilherme Estevam, Leonardo Evangelista e Pâmela Barbosa.

## 1) Requisitos Mínimos do Programa:
1. Usuários devem ser identificados por id e senha.
2. A aplicação deve permitir inserir e apagar contatos e atualizar dados de um contato.
3. O sistema deve oferecer eficientes mecanismos de busca de dados.
4. Deve-se poder fazer listagens de todos os contatos, por grupo de contato ou por campo (ex: nome, CEP, cidade, etc.)
5. Uma interface de usuário prática e atraente.

## 3) UML:
a. Desenvolver os casos de uso do sistema.


![alt text](https://github.com/BrunoDuzanjo/ProjetoEngenhariaDeSoftware/blob/main/Imagens/Diagrama%20de%20caso%20de%20uso.png)


b. Elaborar diagramas de sequência para os casos de uso mais importantes.


Diagrama de sequência (criar contato)


![alt text](https://github.com/BrunoDuzanjo/ProjetoEngenhariaDeSoftware/blob/main/Imagens/Diagrama%20de%20sequ%C3%AAncia%20b%C3%A1sico.png)


Diagrama de sequência (login)


![alt text](https://github.com/BrunoDuzanjo/ProjetoEngenhariaDeSoftware/blob/main/Imagens/Diagrama%20de%20sequ%C3%AAncia%20login.png)


Diagrama de sequência (Criar Grupo de contatos)


![alt text](https://github.com/BrunoDuzanjo/ProjetoEngenhariaDeSoftware/blob/main/Imagens/Diagrama%20de%20sequ%C3%AAncia%20grupo%20de%20contatos.png)


c. Elaborar diagramas de atividade.


![alt text](https://github.com/BrunoDuzanjo/ProjetoEngenhariaDeSoftware/blob/main/Imagens/Diagrama%20de%20atividade.png)


d. Elaborar os diagramas de classe do sistema.


![alt text](https://github.com/BrunoDuzanjo/ProjetoEngenhariaDeSoftware/blob/main/Imagens/Classe%20UML.png)


e. Elaborar os diagramas de estado de um objeto Conta (Account)


![alt text](https://github.com/BrunoDuzanjo/ProjetoEngenhariaDeSoftware/blob/main/Imagens/Diagrama%20de%20Estado.png)


f. Explicitar a arquitetura escolhida. Nela você deverá explicitar os módulos do sistema, sempre
respeitando o padrão arquitetural escolhido (4-Layer, Transaction Scripts, Domain Model, etc). Use, para
tal, diagramas de componentes e/ou de pacotes.


 - Para fazer o projeto, utilizamos o padrão de design MVC, os models, foi com banco de dados, as views sendo as telas mostradas ao usuário e o controller sendo as interações com contatos.


![alt text](https://github.com/BrunoDuzanjo/ProjetoEngenhariaDeSoftware/blob/main/Imagens/Diagrama%20de%20Componentes.png)


g. Elaborar os diagramas de implantação (deployment), para especificar em que máquinas (virtuais,
containers, cloud, etc) e recursos os componentes desenvolvidos no item anterior devem ser alocados.


![alt text](https://github.com/BrunoDuzanjo/ProjetoEngenhariaDeSoftware/blob/main/Imagens/Diagrama%20de%20Implanta%C3%A7%C3%A3o.png)

---------

<a href="https://www.bing.com/aclick?ld=e8aClZuBIAeHChT3qB71jlYDVUCUwRk6D4PvBklf3Rk33iW4nGU-G35L9xvigGXCrjyMtuUb4GxRm0qtwSlIJMQ3tjty55fpJM2e-9wr8LDeB4ghntp-45S7Abf4jLPst6DMtpDlqmq9hf3FTPsFjIU3FAT_4oe3EiVJBhU41lxWGpGpx1&u=aHR0cHMlM2ElMmYlMmZ3d3cubHVjaWRjaGFydC5jb20lMmZwYWdlcyUyZnB0JTJmbGFuZGluZyUzZnV0bV9zb3VyY2UlM2RiaW5nJTI2dXRtX21lZGl1bSUzZGNwYyUyNnV0bV9jYW1wYWlnbiUzZF9wdF9hbGxjb3VudHJpZXNfbWl4ZWRfc2VhcmNoX2JyYW5kX2V4YWN0XyUyNmttX0NQQ19DYW1wYWlnbklkJTNkMzY5NDU5MzU3JTI2a21fQ1BDX0FkR3JvdXBJRCUzZDEyMzgwNTAyNjg2OTU3NDAlMjZrbV9DUENfS2V5d29yZCUzZGx1Y2lkY2hhcnQlMjZrbV9DUENfTWF0Y2hUeXBlJTNkZSUyNmttX0NQQ19CaWRfTWF0Y2hUeXBlJTNkYmUlMjZrbV9DUENfRXh0ZW5zaW9uSUQlM2QlMjZrbV9DUENfTmV0d29yayUzZG8lMjZrbV9DUENfQ3JlYXRpdmUlM2Q3NzM3ODIzMjQzNDE2OCUyNmttX0NQQ19UYXJnZXRJRCUzZGt3ZC03NzM3ODI4NDI3MzgyMiUzYWxvYy0yMCUyNmttX0NQQ19Db3VudHJ5JTNkNjY4JTI2a21fQ1BDX0RldmljZSUzZGMlMjZta3dpZCUzZGVGRzQzdzNTX3BjcmlkXzc3Mzc4MjMyNDM0MTY4X3Brd19sdWNpZGNoYXJ0X3BtdF9iZV9wZHZfY19zbGlkX19wZ3JpZF8xMjM4MDUwMjY4Njk1NzQwX3B0YWlkX2t3ZC03NzM3ODI4NDI3MzgyMiUzYWxvYy0yMF9pbnRlbnRfJTI2bXNjbGtpZCUzZDc4ZjczZDNmMTZmYTEwYjlkZWEyNWRjZmYzNWQ3Y2Jl&rlid=78f73d3f16fa10b9dea25dcff35d7cbe&ntb=1">Lucidchart</a>


