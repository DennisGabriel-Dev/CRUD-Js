# CRUD Assíncrono com JavaScript

Para rodar o projeto você precisa inicialmente instalar o NodeJS:
<br>
https://nodejs.org/en/download/ 
<br>
***obs:escolha de acordo com as configurações da sua máquina;***

Abra o terminal na pasta principal do projeto em: ".../CRUD-Js>"
e dê o comando:
~~~
npm install
~~~
para instalar os módulos do node;

O próximo passo é instalar o json-server: 
~~~
npm install json-server        
~~~

Agora, você precisa instalar o browserSync:
~~~
npm install -g browser-sync
~~~

para "ativar" o banco de dados" use:
~~~
npx JSON-server --watch db.json
~~~

então, logo em seguida rode esse comando para iniciar o sevidor na porta 5000:
~~~
browser-sync start --server --file . --host --port 5000 --startPath /telas/lista_cliente.html
~~~
