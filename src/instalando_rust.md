## Instalación

El primer paso es instalar Rust. Descargaremos Rust a través de `rustup`, una
herramienta de línea de comandos para administrar las versiones de Rust y las
herramientas asociadas. Necesitarás una conexión a Internet para la descarga.

Los siguientes pasos instalan la última versión de Rust, el lenguaje de
programación con el que MDBook está programado. Es necesario tener instalado
Rust para poder instalar y utilizar MDBook.

### Instalación de `rustup` en Linux o macOS

Si estás utilizando Linux o macOS, abre una terminal y escribe lo siguiente

```console
curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | sh
```

El comando descarga un script y comienza la instalación de la herramienta
`rustup`, que instala la última versión estable de Rust. Es posible que se te
solicite tu contraseña. Si la instalación es exitosa, aparecerá la siguiente
línea:

```text
Rust is installed now. Great!
```

### Instalación de `rustup` en Windows

En Windows, ve a [https://www.rust-lang.org/tools/install](https://www.rust-lang.org/tools/install) y sigue las
instrucciones para instalar Rust. En algún momento de la instalación, recibirás
un mensaje que explica que también necesitarás las herramientas de compilación
de MSVC para Visual Studio 2013 o posterior.

Para obtener las herramientas de compilación, deberás instalar [Visual Studio
2022](https://visualstudio.microsoft.com/es/vs/) Community Edition.
Cuando se te pregunte qué paquetes de trabajo instalar, incluye:

* “Desarrollo de escritorio con C ++”
* El SDK de Windows 10 o 11

<a id="solucion-de-problemas"></a>

### Solución de problemas

Para verificar si has instalado Rust correctamente, abra una shell y escribe esta
línea:

```console
rustc --version
```

Si la instalación fue exitosa, verás la versión de Rust que se instaló.

### Actualización de versiones

Una vez que Rust se instala a través de `rustup`, actualizar a una versión
recién lanzada es fácil. Desde tu shell, ejecuta el siguiente script de
actualización:

```console
rustup update
```