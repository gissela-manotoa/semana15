# semana15
semana15
# Crear un diccionario con información ficticia de una persona
informacion_personal = {
    "nombre": "Gissela Manotoa",
    "edad": 30,
    "ciudad": "Madrid",
    "profesion": "Ingeniero"
}

# Acceder y modificar el valor de "ciudad"
informacion_personal["ciudad"] = "Ambato"

# Agregar una nueva clave-valor para "telefono"
if "telefono" not in informacion_personal:
    informacion_personal["telefono"] = "123-456-789"

# Eliminar la clave "edad"
informacion_personal.pop("edad", None)

# Imprimir el diccionario final
print(informacion_personal)
