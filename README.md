# Imagenes-en-Whatsapp-por-link
Se explica como se puede enviar una imagen por whatsapp como link y que se renderice

## Caracteristicas de la imagen

1. Debe ser minimo 200 x 200 pixeles
2. Se recomienda 1200 x 630
3. Se recomienda .png o .jpg
4. Debe estar alojada en un servidor
5. Debe estar publica
6. No puede ser una imagen compartida por google drive

> [!WARNING] 
> El motivo es técnico, pero sencillo de entender:
> Google Drive no da un enlace directo a la imagen: Cuando compartes un enlace de Google Drive, en realidad estás compartiendo un enlace a una página web de Google que muestra tu imagen. 
> El robot de Facebook no puede "ver" la imagen: El robot (crawler) de Facebook, LinkedIn, etc., necesita un enlace directo que termine en .png o .jpg (como el que tienes ahora). No es lo suficientemente "inteligente" para navegar por la página de vista previa de Google Drive y encontrar la imagen dentro.


## Donde se puede validar que esta bien la imagen

1. Se puede usar el link de facebook para validar que la imagen este lista para ser compartida
    [Validar Imagen](https://developers.facebook.com/tools/debug)

Ejemplo de una imagen aprobada y lista para compartir:

![alt text](imagen.png)
