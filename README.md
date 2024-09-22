# Recomendación musical en KKBox

## Índice

- [Descripción](#descripción)
- [Índice](#índice)
- [Instrucciones para el usuario](#instrucciones-para-el-usuario)
- [Instalación](#instalación)
- [Análisis de los datos](#análisis-de-los-datos)
- [Ingeniería de variables](#ingeniería-de-variables)
- [Entrenamiento del modelo](#entrenamiento-del-modelo)
- [Resultados y conclusión](#resultados-y-conclusión)
- [Anexo](#anexo)
    - [Estudios preliminares](#estudios-preliminares)
    - [Elementos no incluídos](#elementos-no-incluídos)
    - [Código](#código)
- [Uso](#uso)
- [Contribuciones](#contribuciones)
- [Licencia](#licencia)

## Descripción

Nuestro dataset consiste en varias tablas con información relativa a canciones, usuarios y escuchas realizadas por estos usuarios en la aplicación KKBox, plataforma musical líder en la mayoría de países asiáticos. El objetivo del trabajo será idear un sistema de recomendación de canciones.

KKBOX proporciona un conjunto de datos de entrenamiento que consiste en información del primer evento de escucha observable para cada par único de usuario y canción dentro de un tiempo específico. El objetivo será predecir las posibilidades de que un usuario escuche una canción repetidamente después de que se active el primer evento de escucha. Si hay eventos de escucha activados dentro de un mes después del primer evento de escucha observable del usuario, su objetivo se marca 1 y 0 de lo contrario en el conjunto de entrenamiento. La misma regla se aplica al conjunto de test.

En resumidas cuentas la meta del trabajo será el estudio del dataset para elaborar un modelo que prediga si un usuario dará más escuchas a una canción que ha sido escuchada una vez por parte del mismo.

La idea de este trabajo tiene su origen en un reto por parte de la conferencia *International Conference on Web Search and Data Mining* (WSDM), que proporciona este dataset donado por la propia aplicación KKBox, a los usuarios de Kaggle ML para elaborar un mejor modelo de recomendación musical que el suyo en 2018.

Pedro Chans Fanego.

## Instrucciones para el usuario

Para poder descargar los datos desde Kaggle, necesitas una API key de Kaggle.

1. Ve a tu cuenta de Kaggle (https://www.kaggle.com/account)
2. En la sección API, haz clic en "Create New API Token". Esto descargará el archivo `kaggle.json`.
3. Coloca el archivo `kaggle.json` en la carpeta `~/.kaggle/` (en sistemas UNIX como Linux/Mac) o en `C:\Users\TU_USUARIO\.kaggle\` (en Windows).
4. Asegúrate de que la carpeta tenga los permisos adecuados (`chmod 600` en UNIX).

## Instalación

Para instalar las dependencias necesarias, ejecuta el siguiente comando:

```sh
pip install -r requirements/requirements.txt
```

## Análisis de los datos

Comenzaremos el trabajo con un breve análisis. Leeremos los datos, mostraremos el tabular, describiremos las columnas e imprimiremos una fila de cada tabla para tener una idea inicial.

## Ingeniería de variables

En esta sección, realizaremos la ingeniería de variables necesaria para preparar los datos para el modelo de aprendizaje automático.

## Entrenamiento del modelo

Entrenaremos varios modelos de aprendizaje automático y seleccionaremos el mejor basado en métricas de rendimiento.

## Resultados y conclusión

Presentaremos los resultados obtenidos y las conclusiones derivadas del análisis y modelado de los datos.

## Anexo

### Estudios preliminares

Incluiremos estudios preliminares realizados durante el análisis de los datos.

### Elementos no incluídos

Mencionaremos elementos que no fueron incluidos en el análisis final.

### Código

Proporcionaremos el código utilizado para el análisis y modelado de los datos.

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue o envía un pull request para contribuir a este proyecto.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.