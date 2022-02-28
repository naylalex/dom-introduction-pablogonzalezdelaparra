# Manejo de imágenes 

Objetivo: Añadir tres imágenes con estilo CSS personalizado para imagen pequeña, mediana y grande.

# Añade elementos con imágenes en el cuerpo del documento HMTL
Los elementos deben tener la siguiente estructura:
```html
<p>Image <n>: style=<STYLE_NAME>
    <img id="image<n>", src="../img/<IMG.jpeg>", class="<SOME_CLASS>">
</p>
```

| Texto del elemento <p> | id de la imagen | clase de la imagen |
| --- | --- | --- |
| Image 4: style=small_img | image4 | small_img |
| Image 5: style=medium_img | image5 | medium_img |
| Image 6: style=large_img | image6 | large_img |

# Implementa los estilos en my_styles.css

Recuerda que las reglas se definen con un selector y en llaves el conjunto de atributos y valores de la regla
```css
.huge_img {
    height: 1024px;
}
```

| Nombre de la regla CSS | Valor del atributo height |
| --- | --- |
| .smallImg | 128px; |
| .mediumImg | 256px; |
| .largeImg | 512px; |

# Añade una referencia a la hoja de estilo en el encabezado del documento HTML
Recuerda que para añadir una referencia a una hoja de estilo usamos el elemento `link`
```html
<link href="<ARCH_CSS>" rel="stylesheet" />

```

# Integra las imágenes nuevas en init() 
* Actualiza la longitud de arrImages.

* Añade los elementos elementos correspondientes a image4, ..., image6 a `arrImages`

* Incluye el nombre de la clase de la imagen en la variable `strHtml` 
```js
//Recuerda que un objeto image tiene el atributo className
img.className
```
