# programaciion_ingenieria_civil.
programa de notebook aplicada en Python
def clasificar_plasticidad(indice_plasticidad):
    if indice_plasticidad < 7:
        return "Baja plasticidad"
    elif 7 <= indice_plasticidad <= 17:
        return "Plasticidad media"
    else:
        return "Alta plasticidad"

# Ejemplo de uso
ip_suelo = 12.5
categoria = clasificar_plasticidad(ip_suelo)
print(f"El suelo tiene una: {categoria}")
