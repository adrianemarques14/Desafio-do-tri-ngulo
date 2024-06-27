a = float(input('Digite o tamanho do lado A do triângulo: '))
b = float(input('Digite o tamanho do lado B do triângulo: '))
c = float(input('Digite o tamanho do lado C do triângulo: '))
if a < b + c and b < a + c and c < a + b:
    print('Os segmentos podem formar um triângulo')
    if a == b and a == c:
        print('Esse triângulo é equilatero!')
    elif a == b and a !=c or a == c and a != b or b == c and a != b:
        print('Esse triângulo é isósceles!')
    else: 
        print('Esse triângulo é escaleno!')
else:
    print('Esses segmentos não podem formar um triângulo')
