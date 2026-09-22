# Web Scraping de Tasas de Interés - SBS Perú

## Descripción

Proyecto de web scraping desarrollado en Python para automatizar la extracción de las tasas de interés activas publicadas por la **Superintendencia de Banca, Seguros y AFP (SBS) del Perú**.

El proyecto permite consultar la información publicada por la SBS para una fecha determinada y obtener las tasas correspondientes según la moneda y el grupo de crédito seleccionado.

## Tecnologías utilizadas

- **Python**
- **SeleniumBase** – automatización e interacción con la página web.
- **BeautifulSoup** – extracción y procesamiento del HTML.
- **Pandas** – estructuración, limpieza y transformación de los datos.
- **Jupyter Notebook** – desarrollo y documentación del proyecto.

## Funcionalidades

El scraper permite consultar las tasas de interés utilizando tres parámetros:

- **Fecha**
- **Moneda**
  - Moneda Nacional (MN)
  - Moneda Extranjera (ME)
- **Grupo de crédito**

### Grupos de crédito

- Corporativos
- Grandes Empresas
- Medianas Empresas
- Pequeñas Empresas
- Microempresas
- Consumo
- Hipotecarios

## Flujo del proyecto

```text
Página web de la SBS
        ↓
Selección de fecha
        ↓
Selección de moneda
        ↓
Extracción del HTML
        ↓
BeautifulSoup
        ↓
Identificación de tablas y categorías
        ↓
Pandas
        ↓
DataFrame estructurado
