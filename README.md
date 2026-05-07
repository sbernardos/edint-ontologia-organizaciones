# Ontología EDINT de Organizaciones Públicas

La ontología de Organizaciones públicas representa el dominio de los organismos públicos (y sus organigramas) en España.
Está siendo desarrollada en el contexto del Espacio de Datos para las Infraestructuras Urbanas Inteligentes ([EDINT](https://edint.es/)).

# Propósito y alcance de la ontología

El propósito de esta ontología es proporcionar un vocabulario común para la representación de las organizaciones públicas en España, así como aspectos relacionados con los organigramas dentro de dichas organizaciones.
Es una actualización de una versión previa de la ontología que extendía la ontología del W3C para organizaciones (W3C Organization Ontology). Esta versión adapta esa ontología para cubrir los requisitos de EDINT.

# Prefijo y espacio de nombres de la ontología

El prefijo de la ontología es: edintorg y se encuentra publicada en el espacio de nombres: http://vocab.linkeddata.es/datosabiertos/def/sector-publico/organizacion#

# Modelo conceptual de la ontología

![Diagrama del modelo conceptual](diagrams/diagrama.png)

# Estructura del repositorio

El repositorio debe contener (al menos) las siguientes carpetas

| Carpeta | Descripción |
|--------|--------------|
| **diagrams/** | Contiene diagramas y otros recursos que representan el modelo conceptual de la ontología (por ejemplo, jerarquías de clases, relaciones). |
| **documentation/** | Contiene la documentación de la ontología y artefactos relacionados en formato HTML o dirigida a usuarios. |
| **tests/** | Contiene las pruebas para la evaluación de la ontología. |
| **kos/** | Contiene la implementación de vocabularios controlados o KOS, generalmente implementaciones SKOS en RDF.|
| **ontology/** | Contiene los archivos de implementación de la ontología en formatos como .owl, .rdf, .ttl o .jsonld |
| **requirements/** | Contiene todos los documentos utilizados para definir los requisitos de la ontología: ejemplos de datos, preguntas de competencia, requisitos funcionales, casos de uso, etc. |
| **shapes/** | Contiene las restricciones SHACL utilizad para validar datos respecto a la ontología.  |

# Mantenimiento del proyecto

Para manejar las incidencias o mejoras sugeridas con respecto a la ontología, recomendamos seguir las guías proporcionadas en ([Issues Management](./ISSUES.md)) para generar una incidencia.

# Financiación

Incluir aquí la información sobre financiación del proyecto e imágenes necesarias.
