# Métodos de Dicionários

```
dados.update({'Passat': 106161.94})
dados                                   #Saída:{'Crossfox': 72832.16, 'DS5': 124549.07, 'Jetta Variant': 88078.64, 'Passat': 106161.94}

dados.update({'Passat': 106161.95, 'Fusca': 150000})
dados                                   #Saída: {'Crossfox': 72832.16, 'DS5': 124549.07, 'Fusca': 150000, 'Jetta Variant': 88078.64, 'Passat': 106161.95}

dadosCopy = dados.copy()
dadosCopy                               #Saída:{'Crossfox': 72832.16, 'DS5': 124549.07, 'Fusca': 150000, 'Jetta Variant': 88078.64, 'Passat': 106161.95}

del dadosCopy['Fusca']
dadosCopy                               #Saída: {'Crossfox': 72832.16, 'DS5': 124549.07, 'Jetta Variant': 88078.64, 'Passat': 106161.95}

dadosCopy.pop('Passat')               #Elimina uma chave do dicionário
dadosCopy.pop('Passat', 'Chave não encontrada')

dadosCopy

dadosCopy.clear()               #Limpa todo o dicionário
dadosCopy
``` 