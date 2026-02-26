# Proyecto-integrador-unidad-1
proyecto basado en la tarea del formulario

El presente proyecto consiste en el desarrollo de un formulario de registro de estudiantes utilizando Python y la biblioteca Flet, tomando como base el diseño mostrado en la imagen de referencia proporcionada por el docente.

El formulario permite capturar información básica del alumno y se mejoró mediante la implementación de validaciones y controles interactivos para garantizar la correcta captura de los datos.

Objetivo del Proyecto

Diseñar una interfaz gráfica funcional que:

Replique el diseño del formulario proporcionado.

Permita capturar datos del estudiante.

Valide la información antes de enviarla.

Muestre los datos registrados en una ventana modal de confirmación.

<img width="785" height="254" alt="image" src="https://github.com/user-attachments/assets/f52162f5-5849-47fa-b7c7-d6ac14b88d72" />


# Estructura del Formulario

# El formulario captura los siguientes datos:

* Nombre

* Número de control

* Email

* Carrera (Dropdown)

* Semestre (Dropdown)

* Género (Radio buttons)


# El programa inicia con la función principal:

<img width="369" height="46" alt="image" src="https://github.com/user-attachments/assets/f73d0cce-53bb-480c-9a7b-ab36489627d3" />



Esta función configura la ventana:

*Título de la página.

*Color de fondo.

*Márgenes.

*Alineación de los elementos.

*Tema visual claro.


# Creación de los Campos de Entrada

Se utilizan controles TextField para capturar texto:

* txt_nombre → Solo acepta letras.

* txt_control → Configurado para entrada numérica.

* txt_email → Para correo electrónico.

Cada campo incluye:

* Etiqueta (label)

* Texto de ayuda (hint_text)

* Color personalizado del borde.


# Uso de Controles Especiales
🔽 Dropdown (Listas desplegables)

Se implementaron dos listas:

* Carrera

* Semestre

Esto evita errores de captura porque el usuario selecciona opciones predefinidas.

<img width="404" height="67" alt="image" src="https://github.com/user-attachments/assets/947239c9-61b8-4ebb-af9f-44a087cc3ebe" />

# RadioGroup (Selección de género)

Permite elegir una sola opción entre:

*Masculino

*Femenino

*Otro
<img width="356" height="29" alt="image" src="https://github.com/user-attachments/assets/6eff37c8-0a18-4b53-aba1-b37ad3b45caa" />

# Validaciones Implementadas

Las validaciones se ejecutan al presionar el botón Enviar Datos mediante la función:

<img width="294" height="42" alt="image" src="https://github.com/user-attachments/assets/378be684-1efc-4aa3-8739-a0edc80fdfbf" />

1️⃣ Validación de Campos Vacíos

Se verifica que ningún campo esté sin llenar:

<img width="682" height="37" alt="image" src="https://github.com/user-attachments/assets/4fba4039-cb12-47ee-b83b-7cc8d8073b87" />

Si falta información:

Se muestra un SnackBar rojo con el mensaje:

"RELLENA TODOS LOS CAMPOS"
