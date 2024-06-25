# Proyecto-encriptacion-Esteganografia
# Herramienta de Esteganografía en Imágenes

Este proyecto es una aplicación web sencilla que permite a los usuarios ocultar un mensaje dentro de una imagen utilizando técnicas de esteganografía y un cifrado César para la encriptación. El mensaje oculto puede ser extraído de la imagen posteriormente.

## Características

- *Ocultar Mensaje:* Encripta un mensaje usando el cifrado César y lo oculta en una imagen.
- *Extraer Mensaje:* Extrae y desencripta un mensaje oculto de una imagen.
- *Interfaz Fácil de Usar:* Interfaz simple e intuitiva con alertas para guiar a los usuarios.

## Tecnologías Utilizadas

- HTML
- CSS
- JavaScript
- [SweetAlert2](https://sweetalert2.github.io/) para las alertas

## Cómo Funciona

### Ocultar un Mensaje

1. *Cargar una Imagen:* Selecciona un archivo de imagen usando el input de archivo.
2. *Ingresar un Mensaje:* Escribe el mensaje que deseas ocultar en el campo de texto.
3. *Encriptar y Ocultar:* El mensaje se encripta usando un cifrado César con un desplazamiento de 3 y luego se oculta en la imagen modificando los bits menos significativos de los datos de los píxeles de la imagen.
4. *Descargar Imagen:* La imagen modificada se puede descargar, conteniendo el mensaje oculto.

### Extraer un Mensaje

1. *Cargar una Imagen:* Selecciona un archivo de imagen que contenga un mensaje oculto.
2. *Extraer Mensaje:* El mensaje oculto se extrae de los datos de los píxeles de la imagen y se desencripta usando un cifrado César con un desplazamiento de -3.
3. *Ver Mensaje:* El mensaje extraído se muestra en una alerta.
