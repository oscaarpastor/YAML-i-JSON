# YAML y JSON

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

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>





