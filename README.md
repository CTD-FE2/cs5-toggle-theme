# Consigna

[Realizar un script para cambiar tema claro a oscuro](https://drive.google.com/file/d/1c-F_h1MBp4iDZ2jL6RY-cF9cEX5HKKQz/view)

# Posibles soluciones planteadas

1. Desde js ir "harcodeando" los nuevos valores que debe tener cada uno de los elementos. Podemos usar:
    1. `.style = "<codigo css>"`
    2. `.classList.add("<nombres de las clases>")`
2. Agregar un boton, definir las clases en css y toggearlas desde js
    1. `.addEventListener('click', () => {})`
    2. `.onclick = () => {}`