# Changelog

## [Unreleased]

    - Listados y Sublistas de hasta 50.000 registros
    - Desde el desktop habilitar un buscador de opciones/script en función de su título
    - Loaders


## [2023-08-]

### Added

    - Nueva variable de configuración "InactivityMaxLife" para bloquear el sistema si hay un periodo de inactividad determinado.
    - Desde gsShell se puede hacer un preview de imagenes y svg

### Fixed

    - Label [Header]
    - Label [THColSpan] en la salida a pdf
 
### Removed

    - Todo lo relacionado con las tablas gs_pc y gs_pc_inventory


## [2023-08-07]

### Added

    - Se puede cambiar de SubTab con la rueda del ratón
    - Se controla el cierre de sessión directa en los casos de upload en background sin terminar

### Fixed

    - Upload de ficheros en background en modo modificación
    - Tipo de dato number en la clase badge y badgeAsync
    - Se ha modificado el atributo "e-asynchronos" por "e-async"
    - Se han añadido casos de uso a SYS::removeRem()


## [2023-08-04]

### Added

    - Implementación de subida de ficheros de forma asincrona
    - Opción de poder borrar una entrada de idioma desde el formulario

### Fixed

    - Corregido error al abrir editores que ya estaban abiertos
    - Al localizar el fichero de idiomas para las condiciones


## [2023-07-24]

### Fixed

    - Tamaño de objetos


## [2023-07-20]

### Added

    - Icono desde el desktop para el acceso a las últimas descargas y acceder a los procesos ejecutados en segundo plano, la ventana se llama "Download center"
    - Método estático S::multiplePage() para poder ejecutar/conmutar entre multiples páginas
    - Ejecución de múltiples llamadas en segundo plano mediante el metodo S::runBackground()
    - Las fichas de consulta ejecutadas en la ventana de trabajo se podrán ejecutar en segundo plano desde el submenú 
    - Las fichas de consulta ejecutadas en la ventana de trabajo se podrán ejecutar directamente como exportación desde el submenú 

### Fixed

    - Nuevo algoritmo en el desktop para avisar que la sessión caduca
    - grupo de fichas cuando los tag {Z} y {tab} estan consecutivos

## [2023-06-29]

### Added

    - Nueva prestación desde el desktop de opciones en cascada de culquier opción mediante la pulsación de [command/window+click]

### Fixed

    - En los listados error al marcar columna de ordenación
    - Quitado el icono de Modo subWindow en listados directos

## [2023-06-20]

### Fixed

    - Gestión de usuarios
    - Mejoras en el desktop

## [2023-06-18]

### Added

    - Nueva etiqueta [Target] para condicionar la salida en función del número de registros

### Fixed

    - Exportación a formato pdf con tcpdf en versión php8
    - Formatos de exportación

## [2023-06-10]

### Added

    - Se ha añadido la posibilidad de sufijo de imagenes con extensión

## [2023-06-01]

### Added

    - Nueva funcionalidad para refrescar una SubList con eSubListRefresh()
    - Opción para tener una fuente de iconos propios

### Fixed

    - Solucionado el problema exporádico de perder la sesión nada mas entrar, cuando es la primera entrada del dia
    - Validez de la cookie en horas

## [2023-05-21]

### Added

    - Minieditor de [Language] desde el editor pulsando la tecla F2
    - Utilidad de tracear el valor de fields y attributes, con posibilidad de hacer debug
    - Las sublistas se pueden ordenar haciendo click en el TH

### Fixed

    - Solucionado un error al grabar desde el editor cuando se estaba customizado los checkbox

## [2023-05-16]

### Added

    - Se puede definir los dos valores del checkbox

### Fixed

    -Subsanado un problema de javascript con campos con nombre "name"

## [2023-05-07]

### Added

    - La etiqueta [RelationSubList] soporta nombres de campos distintos del padre y del hijo, así como una función de usuario
    - Nueva clase streamerClient() para enviar mensajes desde el servidor al cliente
    - Select y subselect con tablas del engine en un diccionario independiente

### Fixed

    - Solucionado la perdida de sesión
    - Solucionado la creación de sesión con crc erroneo
    - Solucionado la visualización de varios {Tab} consecutivos
    - Idioma base distinto del castellano
    - Eliminado un pixel de separación entre los tab

### Changed
### Removed


## [2023-03-30]

### Added

    - Opción para crear las tablas del engine en un database independiente
    - Filtro dinámico de opciones desde el desktop
    - Vista previa en las opciones del desktop
    - Opciones favoritas
    - Opción de comprimir/expandir cabecera del desktop
    - Opción de fijar o no el menú de opciones del desktop
    - Desde las Migas se puede ver y ejecutar el submenú donde está incluido la opción actual
    - Desde el login en el caso de ser el servidor de desarrollo se puede memorizar el login y el password
    - Opción en el editor de abrir la ayuda en un tab nuevo
    - Los select y subselect en los modos de consulta y confirmar la baja puedes llevar a todas las opciones
    - Incorporación en el editor de una etiqueta para usar Mermaid
    - Incorporación en la ventana de selección de icono para las opciones de un buscador interactivo, así como una columna de preselección y otra de los iconos usados en el árbol de opciones
    - Crear app desde la linea de comandos
    - Login en dos pasos

### Fixed

    - Solucionado errores en la grabación de los usuarios de desarrollo
    
### Changed

    - Mejorada la seguridad en el login
    - Eliminación del uso de cookies
    - Se ha cambiado las variables de sesión por la clase SESS
    - Se ha cambiado las variables de configuración por la clase SETUP

### Removed
