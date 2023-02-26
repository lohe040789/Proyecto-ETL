# Proyecto-ETL
![ETL](https://github.com/lohe040789/Proyecto-ETL/blob/main/Imagenes/ETL-e1563879776366.jpg?raw=true)

En el siguiente proyecto, utilizaremos 3  metodos de extraccion de datos para formar una base de datos.
Posteriormente se realiza un proceso de ETL, donde se efectúa los cambios y normalizados necesario para la base de datos.

El 1ª metodo usado fue scraping a la base de datos de 'https://www.bedca.net/' donde utilizamos la libreria selenium para la obtencion de ciertos productos e ir alimentando nuestra base de datos. 
`scrapingProductos.ipynb`
![Scraping](https://github.com/lohe040789/Proyecto-ETL/blob/main/Imagenes/scraping.png?raw=true)

El 2ª metodo fue encontra una URL('https://zenodo.org/) que nos permitiera descargar un CSV, tratarlo como un DataFrame y con la libreria Pandas limpiarlo. 
`csvRecetas.ipynb`
![Api](https://github.com/lohe040789/Proyecto-ETL/blob/main/Imagenes/api.png?raw=true)


El 3ª metodo fue consultar la API 'https://api.edamam.com/api/nutrition-data' el cual seguimos un tutorial para poder consultar desde recetas y tablas de composicion de los alimentos.
`ApiExtraccion.ipynb`

Posteriormente todos los datos seran cargados a una base de datos creada en MySQL Workbench

## Base de datos 🚀

Crear una base de datos que contenga productos alimenticios, asi como su composiciones y posibles recetas con el uso de los mismos productos.
`ProductosEnSQL.mwb.bak`