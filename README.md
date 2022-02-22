### Introdução ao YAML ###


## O que é YAML?

* Uma linguagem de serialização, seu nome é YAML ain't Markup Language
(YAML não é uma linguagem de marcação)

* Usada geralmente para arquivos de configuração, inclusive do Docker 
para configurar o Docker Compose

* É de fácil leitura para nós humanos

* A extensão dos arquivos é yml ou yaml


## Espaçamento e Identação

* O fim de uma linha indica o fim de uma instrução, não há ponto e vírgula 

* A identação deve conter um ou mais espaços, e não devemos utilizar tab

* E cada uma define um novo bloco

* O espaçamento é obrigatório após a declaração da chave



## Comentários

* Podemos escrever comentários no YAML também, utilizando o símbolo #

* O processador de YAML ignora comentários

* Eles são úteis para escrever como o arquivo funciona/foi configurado

## Dados numéricos

* Em YAML podemos escrever dados numéricos com:

* Inteiros = 12

* Floats = 15.8

## Strings

* Em YAML podemos escrever textos de duas formas

* Sem aspas: este é um texto válido

* Com aspas: "e este também"

## Dados nulos

* Em YAML podemos definir um dado como nulo de duas formas

* ~ ou null

* Os dois vão resultar em None, após a interpretação 


## Booleanos

* Podemos inserir booleanos em YAML da seguinte forma

* True e On = verdadeiro

* False e off = falso

## Arrays

* Os arrays, tipos de dados para listas, possuem duas sintaxes

* Primeira: [1,2,3,4,5]

* Segunda: 
items:
- 1
- 2
- 3
