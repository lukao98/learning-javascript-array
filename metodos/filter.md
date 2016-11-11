#filter()
Este metodo filtra um array testando todos os elementos podendo originar um novo ou alterar o mesmo contendo apenas os elementos que passaram no teste.

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
