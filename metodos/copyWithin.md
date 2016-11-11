#copyWithin()
Este metodo copia os elementos do array para dentro do mesmo array criando uma sequencia onde você determina o inicio, onde será aplicado e o fim da sequência, seguindo a seguinte sintaxe: nomedoArray.copyWithin(target, start, end);  

| Parametro     | Descrição                       | Opcional |
|---------------|:-------------------------------:|----------| 
| target        | Para onde será copiado          | Não      |
| start         | De onde começará a ser copiado  | Não      |
| end           | Posição para parar              | Sim      |  

###Exemplo
```javascript  
var nomes = ['Rollo', 'Lagertha', 'Ragnar', 'Bjorn', 'Floki'];  
nomes.copyWithin(0,3,4);
>Bjorn, Lagertha, Ragnar, Floki  
```

