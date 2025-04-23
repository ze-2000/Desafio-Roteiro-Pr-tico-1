# Desafio-Roteiro-Pratico-1

Apresentação com variáveis em Python:

Use variáveis como nome, idade, curso etc. para se apresentar com print().

Média de valores de uma lista:

python
Copiar
Editar
lista = [10, 20, 30, 40]
media = sum(lista) / len(lista)
print("Média:", media)
Comparar gastos de João e Pedro:

python
Copiar
Editar
joao = [200, 150, 300, 250]
pedro = [180, 160, 320, 270]
soma_joao = sum(joao)
soma_pedro = sum(pedro)
if soma_joao > soma_pedro:
    print("João gastou mais")
elif soma_joao < soma_pedro:
    print("Pedro gastou mais")
else:
    print("Ambos gastaram o mesmo")
