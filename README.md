# Mapa do Brasil SVG
Mapa do Brasil em SVG com nome e código do IBGE.

### DEMO

[https://jsfiddle.net/LucasBassetti/qrd0nvx2/2/](https://jsfiddle.net/LucasBassetti/qrd0nvx2/2/)

### Exemplo de Iteração

``` javascript
(function() {
  
  var states = document.getElementsByClassName("estado")
  
  for(var i = 0; i < states.length; i++) {
    states[i].onclick = function() {
    	alert(this.getAttribute('name') + ' ' + this.getAttribute('code'));
    }
  }
  
})();
```

### Créditos

Mapa Original: [https://github.com/felipeduardo/mapa-brasil-svg](https://github.com/felipeduardo/mapa-brasil-svg)
