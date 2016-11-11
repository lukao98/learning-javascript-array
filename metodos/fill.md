#fill()
Este metodo faz jus ao nome, ele preenche os elementos do array com um valor **estático**. Caso você queira ter um controle do preenchimento, pode-se adicionar um indice de inicio e um indice de parada. Sintaxe do fill com os indices: *nomedoArray.fill(value, start, end)*. 

###Exemplo  
Vamos primeiro testar o fill sem indices de controle:

```javascript
var letras = ['a', 'e', 'i', 'o', 'u'];
letras.fill('c');
console.log(letras);
>c,c,c,c,c
```
Vamos agora testar com os indices
```javascript
var numeros = [1, 2, 3, 4];
numeros.fill(5, 1, 2);
console.log(numeros);
>1,5,5,4
```
