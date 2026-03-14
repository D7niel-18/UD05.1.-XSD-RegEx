# UD05.1.-XSD-RegEx
- Nombre: Daniel Jiménez Ramírez
- Profesor: Willman Acosta
- Actividad: UD05.1.: XSD + RegEx
---
# Descripción de la actividad
Esta actividad trata sobre la creacion de un archivo XML que contiene informacion de varios usuarios y un XSD que valida que los datos sean correctos. Su objetivo es hacer que se cumpla el formato correcto mediante restricciones y expresiones regulares.
---
# Explicación
- Correo electronico: Usa esta expresion ^\S+@\S+\.\S+$. Que significa que se puede introducir uno o mas caracteres que no sean espacios luego la (usuario) @ volvemos otra vez a decir que se puede introducir uno o mas caracteres que no sean espacios (gmail) seguido va el . y nuevamente se puede introducir uno o mas caracteres que no sean espacios (com)
- Numero telefono: Usa esta expresion [0-9]{3}[\s]?[0-9]{3}[\s]?[0-9]{3}. Cualquier dígito del 0 al 9 Exactamente 3 veces, un espacio en blanco opcional, asi sucesivamente hasta el final. Con esto conseguimos que se puedan meter numero de telefono con espacios y sin espacios. Ejemplo: 123 123 123 o 123123123.
- Código Postal: Se usa esta expresion (0[1-9]|[1-4][0-9]|5[0-2])[0-9]{3}. Que significa que dentro de los parentesis hay 3 posible opciones separados por | que significa o, empieza por numero de 01 al 09 luego del 10 al 49, luego del 50 al 52 y el final 3 numeros cualquiera.
- Nombre usuario: Se utiliza esta expresión [a-zA-Z0-9]{5,15}. Que significa una cadena de entre 5 y 15 caracteres que puede tener mayusculas y minusculas de entre la A y la Z y puede contener numeros.
- Contraseña: Se utiliza esta expresión [A-Za-z0-9]{1,}. Es lo mismo que el nombre de usuario pero a diferencia que como minimo tenga 8 cararectes.
---
# Editor y tecnologias usadas en la actividad.
- Visual Studio Code
- XML y XSD
---
