#find()
Similar ao find, este metodo procura em um array o primeiro elemento que atenda ao teste submetido. Caso não seja encontrado nenhum valor, você receberá uma resposta *-1*.

###Exemplo
```javascript
var numeros = [1, 2, 3, 5];

function testePar(numbers)
{
	return numbers%2 === 0;
}

var teste = numeros.find(testePar);
console.log(teste);
>1
```