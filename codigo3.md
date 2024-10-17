# Definir un diccionario con precios de frutas
precios_frutas = {
    'manzana': 2.5,  # Precio por kilo
    'plátano': 1.2,
    'naranja': 1.5,
    'fresa': 3.0
}

# Pedir al usuario que introduzca una fruta
fruta = input("Introduce el nombre de la fruta: ").lower()  # Convertir a minúsculas para evitar problemas de coincidencia

# Verificar si la fruta está en el diccionario
if fruta in precios_frutas:
    # Pedir el número de kilos
    kilos = float(input("Introduce el número de kilos: "))
    
    # Calcular el precio total
    precio_total = precios_frutas[fruta] * kilos
    
    # Mostrar el precio
    print(f"El precio de {kilos} kilos de {fruta} es: {precio_total:.2f} euros.")
else:
    # Mensaje si la fruta no está en el diccionario
    print("La fruta no está en el diccionario.")
    ![image](https://github.com/user-attachments/assets/9caadcbe-919d-437c-a73e-ad929ea67182)
