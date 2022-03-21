# Operações com Dicionários

```
dados = {'Jetta Variant': 88078.64, 'Passat': 106161.94, 'Crossfox': 72832.16}
dados

dados['Passat']         #Saída:106161.94. Quando queremos acessar uma informação dentro desse dicionário.

`Passat' in dados       #Saída: True. Verificarmos se determinada chave está presente naquele dicionário.

len(dados)              #Saída: 3. Número de pares chave-valor

dados['DS5'] = 124549.07    #Incluir itens no dicionário.
dados

del dados['Passat']         #Deletar dados no dicionário.
dados
```