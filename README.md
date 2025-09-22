import math

# Pedir datos al usuario
a = int(input("Ingresa el primer número entero: "))
b = int(input("Ingresa el segundo número entero: "))

# Calcular el MCM usando la relación: MCM(a, b) = |a * b| / MCD(a, b)
mcm = abs(a * b) // math.gcd(a, b)

# Mostrar resultado
print(f"El Mínimo Común Múltiplo (MCM) de {a} y {b} es: {mcm}")
