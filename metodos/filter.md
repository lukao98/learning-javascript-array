#filter()
Este metrodo filtra um array podendo originar um novo ou alterar o mesmo.

###Exemplo
Vamos dar um exemplo alterando um só array: 
```javascript
var numeros = [1, 2, 10, 20];

function Filtrando(numbers)
{
	return numbers >= 10;
}

numeros.filter(Filtrando);
console.log(numeros);
>10,20
```
