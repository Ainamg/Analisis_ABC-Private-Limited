# Analisis Compras ABC Private Limited
Este proyecto tiene como objetivo analizar el comportamiento de compra de los clientes de ABC Private Limited en relación con varios productos de diferentes categorías durante un mes.

## Descripción del Proyecto
El análisis del total de compras busca predecir la cantidad de compra de los clientes frente a varios productos para crear una oferta personalizada. El resutado final de este proyecto es un dashboard que permite visualizar métricas clave, análisis descriptivos y gráficos interactivos para comprender el comportamiento de los clientes.

## Estructura del Proyecto

```bash
Analisis_ABC-Private-Limited
|- Data/   # Carpeta con los archivos utilizados
|  |- Data_raw   # Carpeta con los archivos originales
|  |- |- ABC_datos.xlsx
|  |- Data_analisis   # Carpeta con los datos transformados y el dashboard
|  |- |- ABC_compras_analisis.xlsx
|- Informe explicativo del análisis.docx
|_ README.md
```

## Estructura de Datos

El archivo de datos original consta de varias columnas:
-	**User_ID**: ID del cliente asignado por la empresa
-	**Product_ID**: referencia del producto
-	**Gender**: género. Hay M y H.
-	**Age**: edad. Variable de intervalos
-	**Occupation**: ya se convirtió de valor categórico a columna numérica. Hay 20 profesiones distintas en el estudio.
-	**City_Category**: hay 3 tipos de ciudad. Los que viven en la ciudad A, los que viven en la ciudad B y los que viven en la ciudad C
-	**Stay in Current City Years**: número de años que llevan viviendo en la ciudad.
-	**Marital_Status**: 0 soltero y 1 casado
-	**Product Category 1**: ya se convirtió de valor categórico a columna numérica.
-	**Product Category 2**: ya se convirtió de valor categórico a columna numérica.
-	**Product Category 3**: ya se convirtió de valor categórico a columna numérica.
-	**Purchase**: importe de la compra realizada.

## Desarrollo del Proyecto
- Entendimiento del conjunto de datos y de las columnas.
- Limpieza de los datos
- Análisis descriptivo de las variables numéricas, categóricas y temporales.
- Análisis de la variable objetivo (compras) con las demás variables
- Elección de las columnas relevantes para el dashboard.
- Creación del dashboard

## Conclusiones
- Tenemos un total de compras de 5B.
- El producto 1 es el más comprado.
- Hay diferencias significativas en el gasto según ocupación.
- La mayoría de las compras provienen de la ciudad B.

## Contribuciones
Las contribuciones son bienvenidas. Si deseas mejorar el proyecto, no dudes en ponerte en contacto conmigo o enviar tus ideas.

## Autores
- Aïna [GitHub Profile](https://github.com/Ainamg)

