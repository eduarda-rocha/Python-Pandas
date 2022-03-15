# Seleção de Tuplas

```
nomes_carros = tuple(['Jetta Variant', 'Passat', 'Crossfox', 'DS5'])
nomes_carros

nomes_carros[0]         #Saída: 'Jetta Variant'
nomes_carros[1]         #Saída: 'Passat'
nomes_carros[-1]        #Saída: 'DS5'

nomes_carros[1:3]       #Saída: ('Passat', 'Crossfox')

nomes_carros = ('Jetta Variant', 'Passat', 'Crossfox', 'DS5', ('Fusca', 'Gol', 'C4'))
nomes_carros

nomes_carros[-1]        #Saída: ('Fusca', 'Gol', 'C4')
nomes_carros[-1][1]     #Saída: 'Gol'
``` 