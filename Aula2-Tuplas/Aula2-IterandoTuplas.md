# Iterando em Tuplas

```
nomes_carros = ('Jetta Variant', 'Passat', 'Crossfox', 'DS5')
nomes_carros

carro_1, carro_2, carro_3, carro_4 = nomes_carros   #Desempacotamento de tuplas
carro_1                      #Saída: 'Jetta Variant'
carro_2                      #Saída: 'Passat'
carro_3                      #Saída: 'Crossfox'
carro_4                      #Saída: 'DS5'

_, A, _, B = nomes_carros       #Somente utilizar dois valores da tupla
A                               #Saída:'Passat'
B                               #Saída:'DS5'
_, C, *_ = nomes_carros         #Forma simplificada

carros = ['Jetta Variant', 'Passat', 'Crossfox', 'DS5']
carros
valores = [88078.64, 106161.94, 72832.16, 124549.07]
valores
zip(carros, valores)    #Iterador com tuplas
list(zip(carros, valores))  #transformar esse iterador em uma lista de modo a visualizá-lo

for item in zip(carros, valores):
  print(item)

for carro, valor in zip(carros, valores):
  print(carro, valor)

for carro, valor in zip(carros, valores):
  if(valor > 100000):
    print(carro)
```