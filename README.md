# Programa_Tupla_Contagem_Numero_por_extenso_0_a_20
Programa que tem uma Tupla totalmente preenchida com uma contagem por extenso de ZERO a VINTE.

from time import sleep
tupla = ('Zero', 'Um', 'Dois', 'Três', 'Quatro', 'Cinco', 'Seis', 'Sete', 'Oito', 'Nove', 'Dez',
         'Onze', 'Doze', 'Treze', 'Quatorze', 'Quinze', 'Dezesseis', 'Dezessete', 'Dezoito',
         'Dezenove', 'Vinte')
print('=' * 60)
print('{:^60}'.format('FAZENDO O PYTHON ESCREVER POR EXTENSO DE 0 A 20!'))
print('=' * 60)
sleep(1.5)

while True:
    numeroUsuario = int(input('Digite um número de 0 a 20: '))

    if 0 <= numeroUsuario <= 20:
        break
    print('Tente novamente! ', end='')

print('=' * 60)
print(f'Você digitou o número {tupla[numeroUsuario]}.')
print('=' * 60)
