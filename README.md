# lab06-prompts

Bitacora de ingenieria de prompts

# Bitacora de prompts

Herramienta de IA usada: (copilot)

## Ejercicio 2: Tokens y ventana de contexto

| Texto | Caracteres | Tokens |
| | | |
| Los estudiantes programan en Java. |31 |7 |
| The students program in Java. |30 |6 |
| desafortunadamente |17 | 3|

creé la carpeta de la bitácora dentro del proyecto para organizar los archivos del laboratorio.

abrí Visual Studio Code y verifiqué que el repositorio se clonó correctamente, listo para editar y guardar los avances.

## Ejercicio 3: Temperatura

| Temperatura | % de BiblioTec | Nombres en los 5 intentos                                 |
| ----------- | -------------- | --------------------------------------------------------- |
| 0           | 100%           | BiblioTec, BiblioTec, BiblioTec, BiblioTec, BiblioTec     |
| 0.5         | 83.2%          | BiblioTec, BiblioTec, LibroYa, BiblioTec, BiblioTec       |
| 1           | 50.8%          | BiblioTec, PrestaLibro, BiblioTec, LibroYa, LectoGo       |
| 1.8         | 32.1%          | LectoGo, BiblioTec, NubeDeTinta, PaginaLibre, PrestaLibro |

## Ejercicio 4: Prompt vago vs estructurado

| Criterio                            | Prompt vago | Prompt estructurado |
| ----------------------------------- | ----------- | ------------------- |
| Menciona el objetivo del sistema    | no          | si                  |
| Menciona a los usuarios principales | no          | si                  |
| Tiene exactamente 3 funcionalidades | no          | si                  |
| Esta en 3 parrafos                  | no          | si                  |
| Lo usaria en un informe real        | no          | si                  |

## Ejercicio 5: Anatomia de un prompt

| Componente  | Texto de mi prompt                                                                                  |
| ----------- | --------------------------------------------------------------------------------------------------- |
| Rol         | Actua como desarrollador Java.[cite: 1]                                                             |
| Instruccion | Crea un programa en Java usando una clase Producto con los atributos codigo, nombre, precio y stock |
| Contexto    | para gestionar los productos de una tienda                                                          |
| Ejemplo     | Usa este estilo para los metodos: getPrecio(), setPrecio(double precio)                             |
| Formato     | Explica primero la estructura de la clase y luego presenta el codigo Java                           |

## Ejercicio 6: Del prompt basico al profesional

Actua como desarrollador Java. Crea un ejemplo de login para una aplicacion de escritorio utilizando Swing. El usuario debe ingresar correo y contrasena. Explica brevemente el funcionamiento y presenta el codigo organizado por clases.

Mejora el codigo anterior con estas restricciones: no uses librerias externas, valida que el correo contenga @ y que la contrasena tenga al menos 8 caracteres, y muestra los mensajes con JOptionPane.[cite: 1]

- [Bitacora de prompts](prompts/BITACORA.md)

# Tarea: Mi prompt profesional

## Funcionalidad elegida

Gestión de registro de clientes para un sistema de ventas.
