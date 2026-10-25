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
  honda-logo-horizontal-rojo.png   Honda horizontal (escritorio), rojo #EB212C
  honda-logo-apilado-rojo.png      Honda apilado (móvil), rojo #EB212C
  maquina-motors-logo.png          Maquina Motors sobre fondo blanco opaco, rojo #EB212C
  maquina-motors-logo-blanco.png   Maquina Motors con texto blanco, para modo oscuro
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
