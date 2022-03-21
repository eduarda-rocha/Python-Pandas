# Criando Dicionários

```
carros = ['Jetta Variant', 'Passat', 'Crossfox']
carros
valores = [88078.64, 106161.94, 72832.16]
valores

carros.index('Passat')   #Saída: 1. Acessar o índice

valores[carros.index('Passat')] #Saída: 106161.94

dados = {'Jetta Variant': 88078.64, 'Passat': 106161.94, 'Crossfox': 72832.16}                           #Criacao do dicionario                                                     
dados           

dados = dict(zip(carros, valores))  #Outra forma de criar dicionários
dados
```
