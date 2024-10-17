# puga-fernandez-jorge-kaled1326-3w
# Definimos un diccionario que asocia divisas con sus símbolos
divisas = {'Euro': '€', 'Dollar': '$', 'Yen': '¥'}

# Pedimos al usuario que introduzca el nombre de una divisa
entrada = input("Introduce una divisa (Euro, Dollar, Yen): ")

# Verificamos si la divisa ingresada está en el diccionario
if entrada in divisas:
    # Si está, mostramos el símbolo correspondiente
    print(f"El símbolo de {entrada} es: {divisas[entrada]}")
else:
    # Si no está, mostramos un mensaje indicando que no se encontró
    print("La divisa no está en el diccionario.")
    ![image](https://github.com/user-attachments/assets/36753ae0-9149-4b2b-9e50-606f87797f9e)

