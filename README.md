# Calculator-1-projeto

print('______________-Sua calculadora______________-')
print('Escolha Uma função abaixo: ')
h1 = int(input('[1] Multiplicar\n[2] Somar\n[3] Dividir\n[4]Exponenciação\n[5]Subtração : '))

n1 = float(input('Digite Um número: '))
n2 = float(input('Digite Outro Número: '))

s = n1 + n2
d = n1 / n2
m = n1 * n2
e = n1 ** n2
su = n1 - n2

if h1 >= 6:
    while():
        break
    print('NÚMERO {} Não válido'.format(h1))

if h1 == 1:
    print('A multiplicação entre: {} e {} é {:.2f} '.format(n1, n2, m))

if h1 == 2:
    print('A soma entre {} e {} é {:.2f} '.format(n1, n2, s))

if h1 == 3:
    print('A divisão entre {} e {} é {:.2f} '.format(n1, n2, d))

if h1 == 4:
    print('A exponenciação {} e {} é {:.2f} '.format(n1, n2, e))

if h1 == 5:
    print('A subtração entre {} e {} é {:.2f} '.format(n1, n2, su))
