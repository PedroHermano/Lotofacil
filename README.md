# Lotofacil
# Código para gerar 15 números aleatórios para apostas na Lotofacil.

from random import randint
from time import sleep

numeros = (randint(1, 25), randint(1, 25), randint(1, 25), randint(1, 25), randint(1, 25), randint(1, 25), randint(1, 25), randint(1, 25), randint(1, 25), randint(1, 25), randint(1, 25), randint(1, 25), randint(1, 25), randint(1, 25), randint(1, 25))
print(f'os valores sorteados foram: ', end = " ")
for n in numeros:
    print(f'{n}', end = " ")

sleep(2)
print(f'\n O maior valor sorteado foi {max(numeros)}')
sleep(2)
print(f'O menor valor sorteado foi {min(numeros)}')

print(sorted(numeros))

