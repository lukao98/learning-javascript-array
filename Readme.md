#Arrays
Aqui você aprenderá o que são os arrays, como usar e algumas de suas funções.  
  
#O que é um Array?
Um array é uma lista, ou seja, você pode armazenar diversos valores, sendo eles: **Strings**, **númericos** ou **booleanos**.  

###Exemplo  
Sua mãe pede pra você ir ao mercado e trazer alguns produtos para a casa, para não se esquecer você escreve uma lista. Os produtos são:  
```javascript  
var produto1 = Arroz;  
var produto2 = Feijão;  
var produto3 = Carne;  
```  
Os arrays podem te ajudar armazenando-os em apenas uma variável:  
```javascript  
var lista = ["Arroz", "Feijão", "Carne"];  
```  
Para acessar um item do array você usará um index(indice). Esse index sempre começará do 0, onde o mesmo representa a posição 1 do array.
###Exemplo
```javascript  
var produto1 = lista[0];  
var produto2 = lista[1];  
var produto3 = lista[2];  
```  

#Propriedade Length
Mostra o número de elementos de um array, sendo sempre o valor máximo do index +1, por exemplo: No array *lista* o maior index é 2, então seu length valerá 3 (a contagem sempre começa do 0, lembra?), ou seja, o array *Lista* possui 3 elementos.  
```javascript
console.log(lista.length);
>3
```  
