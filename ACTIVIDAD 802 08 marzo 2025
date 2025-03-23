CALCULADORA EDAD DE MASCOTAS
mascota = input("¿Tu mascota es un perro o un gato? (escribe 'perro' o 'gato'): ").lower()

if mascota in ["perro", "gato"]:
    edad = input(f"Ingresa la edad de tu {mascota} en años: ")
    
    if edad.isdigit():
        edad = int(edad)
        
        if mascota == "perro":
            edad_humana = edad * 7  
        else:
            edad_humana = edad * 5  # Conversión para gatos
        
        print(f"La edad de tu {mascota} en años humanos es aproximadamente {edad_humana} años.")
    else:
        print("Por favor, ingresa un número válido para la edad.")
else:
    print("Solo puedes elegir 'perro' o 'gato'.")
    
CALCULADORA DE PROPINAS
    total_cuenta = input("Ingresa el total de la cuenta: ")

if total_cuenta.replace('.', '', 1).isdigit():
    total_cuenta = float(total_cuenta)
     
    print("Elige el porcentaje de propina: 10, 15 o 20")
    porcentaje_propina = input("Porcentaje: ")

    if porcentaje_propina in ["10", "15", "20"]:
        porcentaje_propina = int(porcentaje_propina)
        
        propina = total_cuenta * (porcentaje_propina / 100)
        total_pagar = total_cuenta + propina
        
        print(f"Propina: ${propina:.2f}")
        print(f"Total a pagar: ${total_pagar:.2f}")
    else:
        print("Porcentaje no válido. Debe ser 10, 15 o 20.")
else:
     print("Por favor, ingresa un número válido para el total de la cuenta.")

    CONTADOR DE PALABRAS MAGICO
    frase = input("Ingresa una frase: ")

palabras = frase.split()

contador = 0
for palabra in palabras:
    contador += 1

print(f"La frase tiene {contador} palabras.")

ERES MAYOR DE EDAD
edad = input("ingresa tu edad: ")
if edad.isdigit():
    edad = int(edad)
    if edad >= 18 and edad <= 21:
        print("puedes entrar al club nocturno pero sin bebidas alcoholicas ")
    elif edad >= 21:
        print("bienvenido")
    else:
        print("no puedes entrar al club nocturno debes ser mayor de edad")

        MAQUINA DE CHISTES
import random

chistes = ["¿Por qué el libro de matemáticas estaba triste? Porque tenía demasiados problemas.",
    "¿Qué le dice un jardinero a otro? ¡Disfrutemos mientras podamos!",
    "¿Cuál es el café más peligroso del mundo? El ex-preso.",
    "¿Cómo se dice pañuelo en chino? Saka-moko.",
    "¿Qué hace una abeja en el gimnasio? ¡Zum-ba!"]

input("Presiona ENTER para escuchar un chiste...")

print(random.choice(chistes))

    print("Por favor, ingresa un número válido para el total de la cuenta.")
