# Guía para concursantes usando PC^2

Guía para los Concursantes usando PC^2, el sistema para competencias de programación.

---

### Requerimientos

Para poder compilar el libro debe tener instalado [node.js](https://nodejs.org), [Git]((https://git-scm.com/downloads)) y [Gitbook Command Line tools](https://github.com/GitbookIO/gitbook-cli)

- Para revisar si el software está instalado, es posible ejecutar los siguientes comandos:
    ```
    $ npm -v
    $ git --version
    $ gitbook -V
    ```

### Instrucciones

El proyecto incluye un conjunto de comandos que automatizan parte del proceso

- **Para instalar o actualizar los plugins** de Gitbook

  ```
  $ npm run docs:prepare
  ```

- **Para visualizar el libro**.
    Este comando ejecuta un servidor web que permite revisar el libro a medida que se escribe.
    Cualquier cambio en el libro se actualiza inmediatamente en el sitio web.

  ```
  $ npm run docs:watch
  ```

- **Para crear el libro** (en Windows)

  ```
  $ npm run docs:build
  ```

- **Para publicar el libro** en el sitio web de Github-Pages (en Windows)

  ```
  $ npm run docs:publish
  ```
