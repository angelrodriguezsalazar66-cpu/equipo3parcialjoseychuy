# Programa de descuentos en una tienda
# Programa echo por los alumnos Jesus Alexander Montero Torres Y Jose Angel Rodriguez Salazar
print("TIENDA DE DESCUENTOS")

# Pedir datos
nombre = input("Ingresa tu nombre: ")
total = float(input("Ingresa el total de la compra: "))
color = input("Ingresa el color de la bolita: ")

# Verificar color y descuento
if color == "roja":
    
    descuento = total * 0.40
    pago = total - descuento

    print("Te ganaste un 40% de descuento")

elif color == "amarilla":
    
    descuento = total * 0.25
    pago = total - descuento

    print("Te ganaste un 25% de descuento")

elif color == "blanca":
    
    descuento = 0
    pago = total

    print("No tienes descuento")

else:
    
    print("Color no valido")
    pago = total

# Mostrar resultados
print("---------------------------")
print("Nombre del cliente:", nombre)
print("Total de compra:", total)
print("Descuento:", descuento)
print("Total a pagar:", pago)
print("---------------------------")
print("Gracias por su compra")
