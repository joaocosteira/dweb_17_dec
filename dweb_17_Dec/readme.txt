no mongo já fizemos o mongo import

tb temos o export pra criar um json



>mongoexport -d database -c coleção -out ficheiro.json 

http://www4.di.uminho.pt/~jcr/Transfers/emds.json

update do file
>json-server -w emds.json

Buscar um dos elems dos ficheiros
http://localhost:3000/emds?_id.$oid=5dd6fbd4eee35a6a2489a454



Instalar a versao da view 4 -> se já tens instalado isto não é retro compativel


>sudo npm i -g @vue/cli 

depois corre 

>vue --version

SFC -> single file component
Componente web que depois via aparecer no browser.

Constituido pelas seguintes componentes:
-template(descrever a estrutura) -> html + js + css
-script(de controlo) -> js
-style(design local) -> css


App.vue 

Criar a App

>vue create emd

>cd emd 
>npm run serve
>ctr c 
>vue add vuetify
>vue add router

voltar a correr 

>npm run serve

