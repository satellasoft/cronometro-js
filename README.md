# Cronometro JS

### Esse script faz parte de uma videoaula publicada no canal SatellaSoft, que por sua vez, ensina a como criar um cronometro com Javascript.

> Youtube vídeo: https://youtu.be/QSW1374FCt4

> SatellaSoft: https://satellasoft.com

# Modo de utilização

> Não será descrito a funcionalidade de cada linha, pois no arquivo cron.js, está completamente comentado, então, abaixo você confere as funções necessárias para iniciar, pausar e parar o contador.

Incorpore o script cron.js a sua página HTML, recomendamos colocar antes do fechamento da tag body. 

```html
<script src="cron.js"></script>
</body>
```

Chame uma das funções abaixo para executar determinada ação.

### Iniciar o contador

```javascript
start();
```

### Pausar o contador

```javascript
pause();
```


### Parar o contador

```javascript
stop();
```

A função timer é responsável por calcular o tempo, ela possui ainda, uma instrução para exibir o resultado em um elemento cujo atributo o ID é **counter**. Está função retorna também, o valor devidamente formatado, caso você precise utilizar em outro lugar.
