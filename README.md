# Operaciones-Python
Pedir dos números al usuario y devolver, suma, multiplicación y si uno es mayor que el otro

#Pedir números al usuario

primer_numero = int(input("Ingresa un número (1): " ))
segundo_numero = int(input("Ingresa un número (2): " ))

#Operaciones aritméticas
print(f'La suma es: {primer_numero + segundo_numero} ')
print(f'La multiplicación es: {primer_numero * segundo_numero}')

#Operaciones de comparación
print(f'¿los números son iguales?: {primer_numero == segundo_numero}')
print(f'¿El primer número es menor que el segundo?: {primer_numero < segundo_numero}')
print(f'¿El segundo número es mayor o igual al primero?: {segundo_numero >= primer_numero}')
