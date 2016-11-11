#every()  
Este metodo testa **todos** elementos de um array. Ele retornará *true* se todos os elementos passarem no teste, caso contrário retornara *false*.

###Exemplo  
Vamos testar o *false*:  
```javascript
var numeros = [1, 2, 3, 4, 5, 6];    

function Teste(numbers)
{
	return numbers >= 10;
}

numeros.every(Teste);
>false
```
Agora vamos testar o *true*:  
```javascript
var numeros = [1, 2, 3, 4, 5, 6];    

function Teste(numbers)
{
	return numbers < 10;
}

numeros.every(Teste);
>true
```


