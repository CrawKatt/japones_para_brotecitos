# Instalando MDBook

MDBook es una herramienta que nos permite crear libros a partir de archivos Markdown.
Para instalar MDBook, debes seguir los siguientes pasos:

## Instalación de MDBook en Linux o macOS

Si estás utilizando Linux o macOS, abre una terminal y escribe lo siguiente

```console
cargo install mdbook
```

El comando instala MDBook y todas sus dependencias.
Una vez instalado, puedes verificar que MDBook se instaló correctamente escribiendo:

```console
mdbook --version
```

Si la instalación fue exitosa, verás la versión de MDBook que se instaló.

## Utilizando MDBook

Para iniciar el libro localmente y ver los cambios en tiempo real, debes ejecutar el siguiente comando:

```console
mdbook serve
```

Este comando abrirá el libro en el puerto 3000 de tu máquina, para ver el libro, debes abrir tu navegador y escribir la siguiente dirección:

```
http://localhost:3000
```

Si realizas algún cambio en el libro, el navegador se actualizará automáticamente.