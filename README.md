# n2-introducao-node

## Resumo das aulas da semana 27 - 31/05


RECAP - O que a gente aprendeu ontem? (27/05)

- node é one single thread (só faz um processo por vez, uma coisinha de cada vez e ele é muito muito muito rapidinho) $;

- o que é NPM?
node package manager - guarda os módulos do node    
- o que é um módulo?
 é um grupo de funções que resolve algum problema

Criamos nosso servidor lindo e maravilhoso
- npm init -y - cria o package.json e o package-lock.json! Trava versões dos pacotes
- npm install (npm i)  - traz as dependencias (ou seja tudo) que mora dentro do package.json)

----------------

- npm install http --save
.gitignore (node_modules)



RECAP  O QUE A GENTE APRENDEU / FIZEMOS ONTEM?! (28/05)


ROTAS? O QUE SÃO ROTAS?
- caminho na URL do nosso navegador ou do POSTMAN
uma rota pode aceitar os métodos HTTP (GET, POST, PUT e DELETE)

/ uma barra sozinha é a raiz (root) do nosso servidor.

Subimos nosso primeiro \o/

O que é um servidor?
Ele recebe, fornece, processa, autoriza acesso a dados (que podem estar no BD ou não) através de:

REQUESTS!
- solicitações de coisas para o nosso servidor que podem ser GETs pra ler dados que tem lá... Podem ser POST para ca

 RESPONSE!!

São as respostas que o nosso servidor oferece para o usuário! E quem é o usuário? Usuário nada mais é do que a pessoa / serviço que fez uma requisição! <3

Podemos também enviar o status code para nossa usuária! Como fazemos isso? Enviamos esse código pelo header, bem como enviar o tipo de conteúdo que estamos passando pela api (HTML. JSON)



Qualidade de vida: use o nodemon para subir o servidor automaticamente conforme salvamos nossas alterações.
criamos um  chamado "start" e passamos o nodemon como comando para iniciarmos nosso server com npm start


_-------------

Para quem ta tendo problema com o nodemon tem o supervisor

_________________________________________

Só para dizer que estou curtindo sua aula s2 !!! 
Obrigada, de nada! - 
Jô: Servimos bem para servir sempre.
_________________________________________

O que aprendemos ontem? (29/05)

arrays => lista de objetos dentro do servidor para ser lida pelo front-end

CORS => recurso de segurança do browser para evitar que o site faça requisições para um servidor que ele desconhece. Como resolvemos? passamos Access-control-allow-origin

LEIA ME, SOY LEGAL=> {
https://medium.com/@alexandremjacques/entendendo-o-cors-parte-8331d0a777e1
http://www.randrade.net/2016/04/20/cors-o-que-e-isso-e-como-ativa-lo-numa-web-api/
}

A gente aprendeu a devolver um JSON pelo servidor {
    1- informamos que era um JSON através do Content-Type: application/json
    1- no response a gente aproveitou pra converter o nosso array de objetos em JSON, usando o stringify
}

Organizar onde o array de objetos mora = declaramos ele fora da nossa função de GET.

INSTALAMOS O EXPRESS!!!!!!!

Instalamos, usando npm install express --save;
Aprendemos a importar o express dentro do servidor usando o método require
const express = require('express')
import express from 'express' = ES6

Criamos o servidor com express
_____________________________________________

30/05

M V C - Design Pattern
o  i   o	
d  e  n	
e  w  t
l        t
        o
        l
        l
        e
        r

end x send





























