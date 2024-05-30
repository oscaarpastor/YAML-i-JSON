# YAML y JSON

## Tabla de Contenidos
- [Introducción](#introducción)
- [YAML](#yaml)
  - [¿Qué es YAML?](#qué-es-yaml)
  - [Características Principales](#características-principales)
  - [Ejemplo de YAML](#ejemplo-de-yaml)
- [JSON](#json)
  - [¿Qué es JSON?](#qué-es-json)
  - [Características Principales](#características-principales-1)
  - [Ejemplo de JSON](#ejemplo-de-json)
- [Comparación entre JSON y YAML](#comparación-entre-json-y-yaml)
- [Imagen de Ejemplo](#imagen-de-ejemplo)
- [Notas y Consejos](#notas-y-consejos)
- [Información Sacada de](#información-sacada-de)

## Introducción
YAML y JSON son formatos para configurar archivos, enviar datos y guardar información estructurada. Ambos son legibles por humanos y máquinas, pero tienen diferentes características y usos específicos.

## YAML
### ¿Qué es YAML?
YAML (YAML Ain't Markup Language) es un formato de serialización de datos que se utiliza para archivos de configuración y transmisión de datos entre aplicaciones. Es conocido por ser simple y legible.

### Características Principales
- **Legible por humanos**: Diseñado para ser fácil de leer y escribir.
- **Formato de datos**: Utiliza sangrías para representar la estructura de los datos.
- **Soporte para datos complejos**: Admite listas, mapas y escalas.
- **Comentarios**: Permite comentarios, que se inician con el carácter `#`.


### Ejemplo de YAML
```YAML
{
  nombre: Oscar
edad: 18
ciudad: Alzira
hobbies:
  - musica
  - fotos
  - deporte
}
```

## JSON
### ¿Qué es JSON?
JSON (JavaScript Object Notation) es un formato de intercambio de datos ligero y fácil de usar. Es independiente del lenguaje y se utiliza ampliamente en aplicaciones web y APIs para transmitir datos entre el cliente y el servidor.

### Características Principales
- **Ligero**: Formato compacto y eficiente.
- **Independiente del lenguaje**: Compatible con la mayoría de los lenguajes de programación.
- **Estructura de datos simple**: Utiliza objetos (mapas) y arreglos (listas).

### Ejemplo de JSON
```json
{
  "nombre": "Oscar",
  "edad": 18,
  "ciudad": "Alzira",
  "hobbies": ["musica", "fotos", "deporte"]
}
```


# Comparación entre JSON y YAML

| Característica | JSON                              | YAML                                     |
|----------------|-----------------------------------|------------------------------------------|
| Legibilidad    | Legible, pero más verboso         | Muy legible, similar a lenguajes naturales|
| Estructura     | Basado en pares clave-valor       | Basado en indentación                    |
| Comentarios    | No admite comentarios             | Admite comentarios                       |
| Uso Común      | APIs web, transmisión de datos    | Archivos de configuración, datos en reposo|
| Compatibilidad | Ampliamente compatible con lenguajes | Compatible, pero menos que JSON          |

![Imagen de Shrek](https://hips.hearstapps.com/hmg-prod/images/shrek-64f9ceef56099.jpg)

> [!NOTE]
> Hola me llamo oscar y me gusta shreck.

> [!TIP]
> Hola me llamo oscar y me gusta shreck.

> [!IMPORTANT]
> Hola me llamo oscar y me gusta shreck.

> [!WARNING]
> Hola me llamo oscar y me gusta shreck.

> [!CAUTION]
> Hola me llamo oscar y me gusta shreck.


# Informacion sacada de:

https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

