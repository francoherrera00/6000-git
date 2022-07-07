# Git desarrollo colaborativo

## Markdown
Sistema de etiquetado como HTML

# H1
## H2
### H3
#### H4
##### H5
###### H6

**Soy un texto en negrita**
*Soy un texto en cursiva*

### Listas

1. Item
2. Item
3. Item

* Item
* Item
* Item

* ls - Listar directorios
* cd - Cambiar directorios
* cd <directorio>
* cd.. - Salgo del directorio
* clear - Limpiar consola
* mkdir - Creo directorios
* touch - Crea archivo
* rm - Borra archivos
* rm -rf - Borrar directorios
* d: - cambio de partición de disco

### Incluir snippets

``` js
    function hola(){
        saludo = "hola"
        return saludo
    }
```

### Verificar que tengo git

    git --version

### Configuro GIT

    git config --global user.name "<nombre>"
    git config --global user.email "<email>"

### Puedo configurar GIT por repositorio

    git config --local user.name "<nombre>"
    git config --local user.name "<email>"
