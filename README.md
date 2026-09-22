\# Web Scraping de Tasas de Interés - SBS Perú



Proyecto de web scraping desarrollado en Python para extraer las tasas de interés activas publicadas por la Superintendencia de Banca, Seguros y AFP (SBS) del Perú.



\## Tecnologías utilizadas



\- Python

\- SeleniumBase

\- BeautifulSoup

\- Pandas

\- Jupyter Notebook



\## Funcionalidades



El proyecto permite consultar las tasas de interés según:



\- Fecha

\- Moneda

\- Grupo de crédito



\### Grupos de crédito



\- Corporativos

\- Grandes Empresas

\- Medianas Empresas

\- Pequeñas Empresas

\- Microempresas

\- Consumo

\- Hipotecarios



\### Monedas



\- Moneda Nacional (MN)

\- Moneda Extranjera (ME)



\## Ejemplo de uso



```python

df\_corporativos = obtener\_tasas\_sbs(

&#x20;   "15/09/2026",

&#x20;   "MN",

&#x20;   "Corporativos"

)



display(df\_corporativos)

