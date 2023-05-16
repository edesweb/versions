# Changelog

## [Unreleased]

    - Sublistas de hasta 50.000 registros
    - Minieditor de ayudas desde el editor
    - Desde el desktop buscador de opciones/script en función de su título
    - Exportación a formato pdf
    - Log de últimas descargas

## [2023-05-16]

### Added

    - Se puede definir los dos valores del checkbox

### Fixed

    -Subsanado un problema de javascript con campos con nombre "name"

## [2023-05-07]

### Added

    - La etiqueta [RelationSubList] soporta nombres de campos distintos del padre y del hijo, así como una función de usuario
    - Nueva clase streamerClient() para enviar mensajes desde el servidor al cliente
    - Select y subselect con tablas del motor en un diccionario independiente

### Fixed

    - Solucionado la perdida de sesión
    - Solucionado la creación de sesión con crc erroneo
    - Solucionado la visualización de varios {Tab} consecutivos
    - Idioma base distinto del español
    - Eliminado un pixel de separación entre los tab

### Changed
### Removed


## [2023-03-30]

### Added

    - Opción de poder poner todas las tablas del motor en un database independiente
    - Filtro dinámico de opciones desde el desktop
    - Vista previa en las opciones del desktop
    - Opciones favoritas
    - Opción de comprimir/expandir cabecera del desktop
    - Opción de fijar o no el menú de opciones del desktop
    - Desde las Migas se puede ver y ejecutar el submenú donde está incluido la opción actual
    - Desde el login en el caso de ser el servidor de desarrollo se puede memorizar el login y el password
    - Opción en el editor de abrir la ayuda en un tab nuevo
    - Los select y subselect en los modos de consulta y confirmar la baja puedes llevar o no tolas las opciones
    - Incorporación en el editor de una etiqueta para usar Mermaid
    - Incorporación en la ventana de selección de icono para las opciones de un buscador interactivo, así como una columna de preselección y otra de los iconos usados en el árbol de opciones
    - Crear app desde la linea de comandos
    - Login en dos pasos

### Fixed

    - Solucionado un error en la grabación de los usuarios de desarrollo
    
### Changed

    - Mejorada la seguridad en el login
    - Eliminación del uso de cookies
    - Se ha cambiado las variables de sesión por la clase SESS
    - Se ha cambiado las variables de configuración por la clase SETUP

### Removed