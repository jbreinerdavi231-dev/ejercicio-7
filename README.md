# ejercicio-7
numero = int(input("Ingrese un número positivo: "))

while numero <= 0:
    print("El número debe ser positivo.")
    numero = int(input("Ingrese otro número: "))

numero_original = numero
binario = ""

while numero > 0:
    residuo = numero % 2
    binario = str(residuo) + binario

    print(numero, "÷ 2 =", numero // 2, "residuo", residuo)

    numero = numero // 2

print("Resultado binario:", binario)
