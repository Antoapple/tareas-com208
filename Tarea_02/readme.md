# Comentarios sobre tarea 2

**EJERCICIO 1**
    
Intente que el código fuera lo más simple posible, ya que el objetivo de este problema era recorrer un rango. Además, puse hasta el 201 para que pudiera aparecer el número 200 incluido. 


**EJERCICIO 2**

La lógica es muy parecida al anterior, así que mantuve el mismo estilo. Agregué una condición if para filtrar solo los múltiplos de 6 usando el operador módulo (%).


**EJERCICIO 3**

Primero quise que este programa fuera interactivo, así que usé input() para hacerlo más cercano al usuario. Además, usé float() para permitir que el usuario pudiera ingresar números con decimales, no solo enteros. 


**EJERCICIO 4** 

En este ejercicio quería que el programa reaccionara de forma diferente dependiendo de dos factores: la edad del usuario y si le gusta o no la música urbana. Para que el código estuviera más organizado, decidí meter todo dentro de una función llamada evaluar_usuario(). Además, usé input() para hacer el programa interactivo, y int() para convertir la edad a número. Al preguntar por la música urbana, usé .strip().lower() para que no importara si el usuario escribía con mayúsculas o con espacios extra, lo que mejora la experiencia y evita errores. Otra cosa fue la estructura donde elegí un if general para separar entre mayores y menores de edad, y dentro de cada caso, otro if para evaluar si le gusta o no la música urbana. Así podía entregar mensajes más personalizados y amigables, como “¡genial!” o “¡bacán!”, que le dan un tono más cercano y no tan serio. Por último, para las respuestas afirmativas, consideré tanto "sí" como "si", porque sé que muchos usuarios escriben sin tilde.