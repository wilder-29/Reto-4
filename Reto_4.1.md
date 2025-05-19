#Determinar si un número es el código ASCII de una vocal minúscula

def es_ascii_vocal_minuscula(n):
    return n in [97, 101, 105, 111, 117] 
 # a, e, i, o, u

numero = int(input("Ingrese un número entero: "))
print("Es vocal minúscula:", es_ascii_vocal_minuscula(numero))
