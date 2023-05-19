# ProjetoInPython
Neste Projeto o programa começa mostrando uma lista aonde é possível Somar, Multiplicar, Mostrar o Numero maior entre dois numeros. 


from time import sleep #importei a blibloteca Time 
maior = 0
novo = 4
opcao = 0
while opcao != 5:

print('''Escolha a operação
    [ 1 ] SOMAR
    [ 2 ] MULTIPLICAR
    [ 3 ] MAIOR
    [ 4 ] NOVOS NÚMEROS
    [ 5 ] SAIR DO PROGRAMA''')

opcao = int(input('Digite a sua opção: '))

if opcao == 5:
        print('Até uma proxima!')
        break

som1 = int(input('Digite um numero: '))
som2 = int(input('Digite outr numero: '))

if opcao == 1:
        valor = som1 + som2
        print('A soma entre {} + {} é {}'.format(som1, som2, valor))
        sleep(1)    
if opcao == 2:
        valor = som1 * som2
        print('A multiplicação entre {} e {} é {}'.format(som1, som2, valor))
        sleep(1)
if opcao == 3:
    if som1 > som2:
     print('O valor {} é maior que {}'.format(som1,som2))
else:
     print('O valor {} é maior que o {}'.format(som2,som1))
        sleep(1)   
if opcao == 4:
        print('Ok')
        sleep(1)
        
print('{:=^30}'.format('Programa by Ravalia'))
input()
