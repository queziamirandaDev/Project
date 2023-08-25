#Caladora

while True:
     
    numero_1 = input('Digite um numero: ')
    numero_2 = input('Digite um numero: ')
    operador = input('Digite um operador (+-/*): ')

    numeros_validos = None

    num_float = 0
    num_2float = 0

    try:
        num_float = float(numero_1)
        num_2float = float(numero_2)
        numeros_validos = True
    except:
         numeros_validos = None


    if numeros_validos is None:
        print('Um dos dois ou ambos são inavalidos.') 
        continue

    operadores_permitidos = '+-/*'

    if operador not in operadores_permitidos:
        print('Operador inavalido')
        continue

    if len(operador) > 1:
        print('Digite apenas um operador')
        continue

    print('Foi realizado a sua conta, confira o resultado abaixo: ')
    if operador == '+':
       print(num_float + num_2float) 
    elif operador == '-':
        print(num_float - num_2float) 
    elif operador == '/':
        print(num_float / num_2float) 
    elif operador == '*':
        print(num_float * num_2float) 
    else:
        print('error')


    sair = input('Quer sair? [s]im: ').lower().startswith('s')

    if sair is True:
        break
