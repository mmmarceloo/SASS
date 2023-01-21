# SASS
Estudos de SASS

npm i -g sass

tudo o que for fazer é no terminal, eu fazia no bach do git msm

PARA COMPILAR:
EX:
ARQUIVO DE ORIGEM => ARQUIVO DE DESTINO.
sass assets/sass/base.scss assets/css/style.css  

se não quiser gerar o arquivo .map.
sass assets/sass/base.scss assets/css/style.css --no-source-map

Se quiser comprimido: => --style compressed

Para ficar monitorando: => --watch, toda vez que alterar ele ja compila

para monitorar a pasta toda, os aruivos tem que ter o mesmo nome: style.scss/style.css
a sintaxe é assim:
sass --watch assets/sass:assets/css --no-source-map --style compressed
