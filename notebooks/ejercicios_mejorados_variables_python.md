# Ejercicios de uso y manejo de variables en Python (Mejorados)

A continuación, 15 ejercicios revisados con descripciones más detalladas del problema. No se permite usar sentencias condicionales, bucles ni definición de funciones.

1. **Extraer valor numérico y unidad de peso**  
   Tienes la cadena `"75.5kg"`. Separa la parte numérica como un `float` y la unidad como un `str`, y luego construye un mensaje:  
   ```python
   # weight = 75.5, unit = "kg"
   # message = "Peso: 75.5 kg"
   ```

2. **Descomponer dirección postal en componentes**  
   Para la dirección `"Calle 123 #45-67, Bogotá, Cundinamarca, Colombia"`, asigna cada elemento (calle, ciudad, región, país) a variables separadas usando `split` y `strip`, y formatea:  
   ```python
   # street = "Calle 123 #45-67"
   # city = "Bogotá"
   # region = "Cundinamarca"
   # country = "Colombia"
   # formatted = "Calle 123 #45-67 | Bogotá | Cundinamarca | Colombia"
   ```

3. **Convertir lista de pares clave-valor en diccionario tipado**  
   Dada la lista de claves `["producto","precio","stock"]` y valores `["Camisa","39.99","20"]`, crea un diccionario, luego convierte `"precio"` a `float` y `"stock"` a `int`. Extrae esos valores en variables.

4. **Generar iniciales a partir de un nombre completo**  
   Con `full_name = "Eva María López Pérez"`, divide en partes, luego toma la primera letra de cada palabra y concaténalas para obtener `"EMLP"`.

5. **Ordenar tres números y resumir**  
   Teniendo `a, b, c = 15, 7, 22`, usa `sorted` para obtener los valores en orden ascendente y genera el resumen: `"Valores ordenados: 7, 15, 22"`.

6. **Reformatear fecha ISO sin funciones externas**  
   Para `date_str = "20250728"`, usa slicing para extraer año, mes y día, y construye `"28-07-2025"`.

7. **Eliminar tildes y caracteres especiales de un texto**  
   Con `text = "Información áéíóú ñ"`, crea una tabla de traducción y usa `str.translate` para obtener `"Informacion aeiou n"`.

8. **Combinar dos diccionarios y comparar valores antes y después**  
   Dados `dict1 = {"a":1,"b":2}` y `dict2 = {"b":3,"c":4}`, guarda el valor original de `"b"`, fusiona con `{**dict1,**dict2}` y compara `"b"` antes y después.

9. **Transformar lista de cadenas numéricas en tupla de enteros**  
   Con `str_nums = ["10","20","30","40"]`, convierte cada elemento a `int` y empaquíalos en una tupla.

10. **Alinear y dar padding a columnas de texto y números**  
    Para `item = "Producto"`, `quantity = 5` y `price = 3.5`, crea una línea con columnas fijas usando especificadores de formato.

11. **Desempaquetado anidado de datos mixtos**  
    Con `data = ("Alice",[25,"F"],{"city":"Bogotá","zip":"110111"})`, extrae nombre, edad, género, ciudad y código postal.

12. **Rellenar plantilla de texto usando un diccionario**  
    Dado `template = "{name} tiene {n} manzanas."` y `info = {"name":"Juan","n":"3"}`, usa `format_map` para generar `"Juan tiene 3 manzanas."`.

13. **Cálculos precisos con `decimal.Decimal`**  
    Usa `d1 = Decimal("0.1")` y `d2 = Decimal("0.2")` para calcular la suma y la resta con precisión exacta.

14. **Formatear fecha y hora con `datetime.strftime`**  
    Con `dt = datetime.datetime(2025,7,28,15,30)`, genera la cadena `"28/07/2025 15:30"`.

15. **Codificar y decodificar texto en bytes UTF-8**  
    Con `text = "hola"`, convierte a bytes y luego de vuelta a cadena, verificando que coincida.
