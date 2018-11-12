# Newspaper-Cover-Scraping
Extraction of articles from the covers of the main digital newspapers of Spain.
![medios](https://user-images.githubusercontent.com/44545128/48369280-66ec5200-e6b6-11e8-91be-61bf40cbccea.jpg)

## English
### Description
The objective of this work is to implement in python 3, a scraper that extracts the data from the cover pages of different media. For this we will use a jupyter notebook.

This jupyther notebook in python 3, creates a table with the data of the articles of the cover of the following digital newspapers: [EL PAIS](https://elpais.com/), [EL CONFIDENCIAL](https://www.elconfidencial.com/), [ELDIARIO.ES](https://www.eldiario.es/) y [EL MUNDO](https://www.elmundo.es/)

From each article we collect the newspaper to which it belongs, the date and time in which the articles of all the newspapers are collected, the name of the article the author, its href, if the article has an image, the name and its href are collected.

This data are stored in a panda dataframe in the following columns: medio, time, titulo_articulo, autor_articulo, href_articulo, titulo_imagen, imagen.

They are converted to CSV format in the medios.csv file.

The images of the articles are kept in a folder for each newspaper.

With this information we can compare, at each moment, which news is more important for each newspaper, which topics are more interesting, what type of articles have associated images, what type of images each newspaper chooses. 

All these analyzes are beyond the scope of the current work.

### Team members
The work has been developed by ** Esteban Bordallo Valbuena ** individually.

### Source files
The code is implemented in the jupyter notebook ** Newspaper-Cover-Scraping.ipynb **

### Complementary files
* **CSV / medias.csv**: flat file, in CSV format with scraping data.
* **IMAGES / elpais**: images of the cover of EL PAIS on 12/11/2018 at 21:16
* **IMAGES / elconfidencial**: images of the cover of EL CONFIDENCIAL on 12/11/2018 at 21:16
* **IMAGES / eldiario**: images of the cover of ELDIARIO.ES on 12/11/2018 at 21:16
* **IMAGES / elmundo**: images of the cover of EL MUNDO on 12/11/2018 at 21:16

### Licence
The Open Database License **(ODbL)** is a license agreement intended to allow users to freely share, modify, and use this Database while maintaining this same freedom for others. Some jurisdictions have specific rights that cover databases, and so the ODbL addresses these rights, too. The ODbL is also an agreement in contract for users of this Database to act in certain ways in return for accessing this Database.

### Resources
1. Subirats, L., Calvo, M. (2018). Web Scraping. Editorial UOC.
2. Github Tutorial https://guides.github.com/activities/hello-world.
3. Beautiful Soup Documentation https://www.crummy.com/software/BeautifulSoup/bs3/documentation.html
4. Beautiful Soup 4.4.0 documentation https://www.crummy.com/software/BeautifulSoup/bs4/doc/

## Español
### Descripción
El objetivo de este trabajo es implementar en python 3, un scraper que extraiga los datos de las páginas de portada de diferentes medios de comunicación. Para ello usaremos un cuaderno de jupyter.

Este jupyther notebook en python 3, crea una tabla con los datos de los articulos de la portada de los siguientes periodicos digitales: [EL PAIS](https://elpais.com/), [EL CONFIDENCIAL](https://www.elconfidencial.com/), [ELDIARIO.ES](https://www.eldiario.es/) y [EL MUNDO](https://www.elmundo.es/)

De cada articulo recogemos el periodico al que pertenece, la fecha y hora en que se recogen los articulos de todos los periodicos, el nombre del articulo el autor, su href, si el articulo tiene imagen, se recoge el nombre y su href.

Los datos se gardan en un panda dataframe en las siguientes columnas: medio, time, titulo_articulo, autor_articulo, href_articulo, titulo_imagen, imagen.

Se transforman a formato CSV en el fichero medios.csv.

Las imagenes de los articulos se guardan en una carpeta para cada periodico.

Con esta información podemos comparar, en cada instante, que noticias son mas importantes para cada periodico, que temas interesan mas, que tipo de articulos llevan asociados imagenes, que tipo de imagenes elige cada periodico. 

Todos estos analisis escapan al objetivo del trabajo actual.

### Miembros del equipo
El trabajo ha sido desarrollado por **Esteban Bordallo Valbuena** de forma individual.

### Ficheros del código fuente
El código esta implementado el cuaderno jupyter **Newspaper-Cover-Scraping.ipynb**

### Ficheros complementarios
* **CSV / medios.csv** : fichero plano, en formato CSV con los datos del raspado.
* **IMAGES / elpais** : imgenes de la portada de EL PAIS el dia 12/11/2018 a las 21:16
* **IMAGES / elconfidencial** : imgenes de la portada de EL CONFIDENCIAL el dia 12/11/2018 a las 21:16
* **IMAGES / eldiario** : imgenes de la portada de ELDIARIO.ES el dia 12/11/2018 a las 21:16
* **IMAGES / elmundo** : imgenes de la portada de EL MUNDO el dia 12/11/2018 a las 21:16

### Licencia
La licencia de base de datos abierta **(ODbL)** es un acuerdo de licencia destinado a permitir que los usuarios compartan, modifiquen y utilicen esta base de datos de forma gratuita mientras mantienen esta misma libertad para otros. Algunas jurisdicciones tienen derechos específicos que cubren bases de datos, por lo que la ODbL aborda estos derechos también. El ODbL también es un acuerdo en el contrato para que los usuarios de esta base de datos actúen de ciertas maneras a cambio de acceder a esta base de datos

### Recursos
1. Subirats, L., Calvo, M. (2018). Web Scraping. Editorial UOC.
2. Tutorial de Github https://guides.github.com/activities/hello-world.
3. Beautiful Soup Documentation https://www.crummy.com/software/BeautifulSoup/bs3/documentation.html
4. Beautiful Soup 4.4.0 documentation https://www.crummy.com/software/BeautifulSoup/bs4/doc/



