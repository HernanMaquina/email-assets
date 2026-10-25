# Email assets · Honda Maquina Valencia

Imágenes públicas para los emails de Honda Maquina Valencia (Maquina Motors).
Se sirven con GitHub Pages para que se vean en Gmail, Outlook y cualquier cliente de correo.

Las plantillas de email están en el repo privado `email-templates`.

## Dirección de cada imagen

```
https://hernanmaquina.github.io/email-assets/<carpeta>/<archivo>.png
```

Por ejemplo: `https://hernanmaquina.github.io/email-assets/logos/maquina-motors-logo.png`

## Contenido

```
logos/
  honda-logo-horizontal-rojo.png   Honda horizontal (HONDA a la derecha del ala), rojo #EB212C
  maquina-motors-logo-contorno.png Maquina Motors transparente con un contorno blanco de 1 px en las partes negras:
                                   igual que el original sobre blanco y legible si un cliente oscurece el fondo (cabecera)
  maquina-motors-logo-blanco.png   Maquina Motors con texto blanco, para fondos oscuros
  maquina-motors-logo.png          Maquina Motors con texto negro sobre blanco opaco
fondos/
  blanco.png                       8×8 blanco. Fondo de la cabecera: los clientes en modo oscuro no oscurecen las imágenes de fondo
motos/
  forza-125/
    forza-125-<color>-grande.png   960×540, para la foto principal
    forza-125-<color>-pequena.png  288×162, para el selector de colores
```

## Añadir un modelo

1. Crea la carpeta `motos/<modelo>/` (en minúsculas y con guiones, por ejemplo `motos/nc750x/`).
2. Descarga las fotos oficiales desde el configurador de colores del modelo en honda.es:
   la versión `c3_r.png` para la grande y `c1b2.png` para la pequeña.
3. Nómbralas `<modelo>-<color>-grande.png` y `<modelo>-<color>-pequena.png`.
4. Súbelas a la rama `main`. En un par de minutos estarán publicadas.

Todo lo que se sube aquí es público. No subas nada que no vaya a salir en un email.
