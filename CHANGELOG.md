# Changelog

## [Unreleased]

    - Sublistas de hasta 50.000 registros
    - Minieditor de ayudas desde el editor
    - Desde el desktop buscador de opciones/script en funci�n de su t�tulo
    - Exportaci�n a formato pdf
    - Log de �ltimas descargas

## [2023-05-16]

### Added

    - Se puede definir los dos valores del checkbox

### Fixed

    -Subsanado un problema de javascript con campos con nombre "name"

## [2023-05-07]

### Added

    - La etiqueta [RelationSubList] soporta nombres de campos distintos del padre y del hijo, as� como una funci�n de usuario
    - Nueva clase streamerClient() para enviar mensajes desde el servidor al cliente
    - Select y subselect con tablas del motor en un diccionario independiente

### Fixed

    - Solucionado la perdida de sesi�n
    - Solucionado la creaci�n de sesi�n con crc erroneo
    - Solucionado la visualizaci�n de varios {Tab} consecutivos
    - Idioma base distinto del espa�ol
    - Eliminado un pixel de separaci�n entre los tab

### Changed
### Removed


## [2023-03-30]

### Added

    - Opci�n de poder poner todas las tablas del motor en un database independiente
    - Filtro din�mico de opciones desde el desktop
    - Vista previa en las opciones del desktop
    - Opciones favoritas
    - Opci�n de comprimir/expandir cabecera del desktop
    - Opci�n de fijar o no el men� de opciones del desktop
    - Desde las Migas se puede ver y ejecutar el submen� donde est� incluido la opci�n actual
    - Desde el login en el caso de ser el servidor de desarrollo se puede memorizar el login y el password
    - Opci�n en el editor de abrir la ayuda en un tab nuevo
    - Los select y subselect en los modos de consulta y confirmar la baja puedes llevar o no tolas las opciones
    - Incorporaci�n en el editor de una etiqueta para usar Mermaid
    - Incorporaci�n en la ventana de selecci�n de icono para las opciones de un buscador interactivo, as� como una columna de preselecci�n y otra de los iconos usados en el �rbol de opciones
    - Crear app desde la linea de comandos
    - Login en dos pasos

### Fixed

    - Solucionado un error en la grabaci�n de los usuarios de desarrollo
    
### Changed

    - Mejorada la seguridad en el login
    - Eliminaci�n del uso de cookies
    - Se ha cambiado las variables de sesi�n por la clase SESS
    - Se ha cambiado las variables de configuraci�n por la clase SETUP

### Removed