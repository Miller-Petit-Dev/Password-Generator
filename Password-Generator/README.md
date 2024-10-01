# Generador de Contraseñas
Este proyecto es una aplicación de consola Java para generar contraseñas aleatorias y realizar comprobaciones de seguridad de las contraseñas.

## Funcionalidades

### 1. Generando una Contraseña:

- El usuario responde con "Sí" o "No" a preguntas sobre el uso de letras mayúsculas, minúsculas, números o símbolos.
- Luego, el usuario ingresa la longitud deseada de la contraseña.
- Se genera un alfabeto de contraseñas en base a las respuestas del usuario, que es una cadena que contiene los caracteres elegidos.
- Se seleccionan y combinan caracteres aleatorios del alfabeto de contraseñas para formar una cadena completamente aleatoria según las preferencias del usuario.
- La contraseña generada aleatoriamente se muestra en la consola.

### 2. Comprobar la seguridad de una contraseña:

La prueba de resistencia se basa en los siguientes criterios:
- La contraseña utiliza letras mayúsculas.
- La contraseña utiliza letras minúsculas.
- La contraseña utiliza números.
- La contraseña utiliza símbolos.
- La longitud de la contraseña es 8 o más (8 es a menudo la longitud mínima requerida para una contraseña decente).
- La longitud de la contraseña es 16 o más (16 se considera la longitud mínima para una buena contraseña).

Estos criterios se utilizan para calcular una puntuación para la contraseña, que determina el mensaje que se muestra al usuario indicando la seguridad de la contraseña (débil/media/buena/excelente).

### 3. Mostrar información útil:

Esta es una característica menor que muestra información al usuario en la consola sobre la seguridad de la contraseña, como evitar usar la misma contraseña dos veces, evitar la repetición de caracteres, patrones de teclado, palabras del diccionario, secuencias de letras o números, etc.
