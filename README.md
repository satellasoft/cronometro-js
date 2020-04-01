# Cronometro JS

### Esse script faz parte de uma videoaula publicada no canal SatellaSoft, que por sua vez, ensina a como criar um cronometro com Javascript.

> Youtube vídeo: https://youtu.be/QSW1374FCt4

> SatellaSoft: https:satellasoft.com

# Modo de utilização

> Não será descrito a funcionalidade de cada linha, pois no arquivo cront.js está completamente comentado, então, abaixo você confere os métodos necessários para iniciar, pausar e parar.

Incorpore o script a sua página HTML, recomendamos colocar antes de do fechamento da tag. 

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

A função timer é responsável por calcular o tempo, ela possui ainda, uma instrução para exibir o contador em um elemento cujo atributo ID é  **counter**. Está funcção retorna também o valor devidamente formatado, caso você precise utilizar em outro lugar.
