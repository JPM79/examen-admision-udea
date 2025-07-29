# Nuevos 15 ejercicios de uso y manejo de variables en Python

Genera soluciones sin usar condicionales, bucles ni funciones personalizadas.

1. **Conversión de temperatura**  
   Dada `temp_f = 98.6`, convierte a Celsius con la fórmula `C = (F-32)*(5/9)` y almacena el resultado en `temp_c`.

2. **Separar usuario y dominio de un correo**  
   Para `email = "usuario@example.com"`, divide en `user` y `domain`.

3. **Construir JSON a partir de un diccionario**  
   Con `data = {"a":1,"b":2}` y usando el módulo `json`, genera la cadena JSON `json_str`.

4. **Extraer subdominio y dominio principal de una URL**  
   Dada `url = "https://blog.ejemplo.com/articulo"`, usa `str.partition` para obtener `subdomain`, `sep`, `rest`, y luego separa el dominio principal.

5. **Calcular porcentaje**  
   Con `parte = 45` y `total = 120`, calcula `percent = parte/total*100` y formatea `"37.50%"` con dos decimales.

6. **Desempaquetado de tupla anidada**  
   Para `nested = (1,(2,(3,4)))`, extrae `a=1`, `b=2`, `c=3`, `d=4`.

7. **Lista de hexadecimales sin bucles explícitos**  
   Con `nums = [15,31,255]`, genera `hex_nums = list(map(hex, nums))`.

8. **Crear conjunto de elementos únicos y contar**  
   Dada `items = ["x","y","x","z","y"]`, crea `unique_items = set(items)` y `count_unique = len(unique_items)`.

9. **Formatear número con separador de miles**  
   Para `num = 1234567`, genera `formatted = f"{num:,}"` para obtener `"1,234,567"`.

10. **Representación binaria de un entero**  
    Con `n = 13`, obtiene `bin_str = bin(n)` y `bit_length = n.bit_length()`.

11. **Ruta de archivo y extensión con `pathlib`**  
    Usando `from pathlib import Path` y `path = Path("/home/user/documento.txt")`, extrae `stem` y `suffix`.

12. **Codificar y decodificar Base64**  
    Con `import base64` y `text = "hola"`, genera `b64 = base64.b64encode(text.encode())` y recupera el texto original.

13. **División de cadenas con separador múltiple**  
    Para `log = "INFO|2025-07-28|Proceso completado"`, usa `split("|")` y asigna `level`, `date`, `message`.

14. **Expansión de tupla con `*` en asignación**  
    Con `values = (1,2,3,4,5)`, asigna `first, *middle, last = values`.

15. **Uso de `fractions.Fraction` para cálculo exacto**  
    Desde `from fractions import Fraction` y `f = Fraction(1,3)`, suma `f + Fraction(2,3)` y almacena en `result`.
