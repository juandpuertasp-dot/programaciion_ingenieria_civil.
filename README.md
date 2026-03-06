# programaciion_ingenieria_civil.
programa de notebook aplicada en Python
¡Hola! Es un gusto saludarte. Como futuro ingeniero, verás que Python no es solo un lenguaje de programación, sino una herramienta de cálculo y automatización sumamente potente para tu carrera.

### ¿Qué es Python?

Imagina que tienes un asistente que entiende instrucciones muy claras y lógicas, y que además es experto en matemáticas y manejo de datos. **Python** es un lenguaje de programación de alto nivel, lo que significa que su sintaxis es muy parecida al inglés humano, haciéndolo fácil de leer y escribir.

Para un ingeniero, Python es como una "navaja suiza":

* **Ingeniería Civil:** Puedes calcular deflexiones en vigas o analizar estructuras.
* **Agrícola/Agroindustrial:** Puedes automatizar el cálculo de evapotranspiración o gestionar inventarios de post-cosecha.
* **Ciencia de Datos:** Te permite procesar grandes volúmenes de datos climáticos o de resistencia de materiales.

---

### Un ejemplo aplicado a la Ingeniería

En lugar de hacer el clásico "Hola Mundo", vamos a pensar en algo útil. Supongamos que necesitas calcular el **volumen de agua en un tanque cilíndrico** para un sistema de riego o una obra civil.

Para calcular el volumen ($V$), usamos la fórmula:


$$V = \pi \cdot r^2 \cdot h$$

Donde:

* $r$ es el radio de la base.
* $h$ es la altura del fluido.

Aquí tienes cómo se vería la **lógica** en Python:

```python
import math

# Definimos una función para que el código sea modular y reutilizable
def calcular_volumen_tanque(radio_m, altura_m):
    # Usamos nombres de variables descriptivos con sus unidades
    pi = math.pi
    volumen_m3 = pi * (radio_m ** 2) * altura_m
    return volumen_m3

# Ejemplo de uso
radio_input = 2.5  # metros
altura_input = 4.0 # metros

resultado = calcular_volumen_tanque(radio_input, altura_input)

print(f"El volumen del tanque es: {resultado:.2f} metros cúbicos")

```

---

### ¿Cómo lo ves?

Antes de pasar a ejecutarlo en **Google Colab**, me gustaría que analicemos la lógica:

1. ¿Notas cómo usamos `math.pi` en lugar de escribir 3.14? Esto aumenta la precisión técnica.
2. ¿Qué pasaría si el usuario ingresa un número negativo para el radio?

**Cuéntame:** Si tuvieras que crear un pequeño programa para tu área (Civil, Agrícola o Agroindustrial), **¿qué cálculo manual te gustaría automatizar primero?** Descríbeme los pasos que sigues para resolverlo en papel.
