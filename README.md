# OpenDataDay2015
Open Data Day (Scraping con programación y sin ella, extracción de datos de PDFs, fuentes de datos comunes)  
  
1. Scraping (definición y conocimientos previos).
2. Scraping para no programadores.
3. Extracción de datos en PDFs.
4. Fuentes de datos comunes.
  
##1. Scraping (definición y conocimientos previos).   
  
##Definición:  

Según Wikipedia: “Web Scraping es una técnica utilizada mediante programas de software para extraer información de sitios web”  

##Conocimientos previos y otros:

###Buenas costumbres en scraping:  

1. Definir previamente lo que se busca. Planificar.  
2. Copiar web.  
3. Conocimientos previos de programación.  
4. Conservar fuentes.  
5. Guardar los datos utilizando estándares.  

###Aspectos legales:  

“no estarán autorizadas la extracción y/o reutilización repetidas o sistemáticas de partes no sustanciales del contenido de una base de datos que supongan actos contrarios a una explotación normal de dicha base o que causen un perjuicio injustificado a los intereses legítimos del fabricante”.  
Artículo 133 del Real Decreto Legislativo 1/1996, de 12 de abril, por el que se aprueba el Texto Refundido de la Ley de Propiedad Intelectual.  

###Planificar:

1. Open project  
2. Redmine  
3. Github  

###Copia web:   

HTTrack  
![httrack](/images/Httrack.png)
Descarga:http://www.httrack.com/page/2/en/index.html  
Manual:http://www.httrack.com/html/fcguide.html  
httrack "http://lujoyglamour.net/" -O "/tmp/www.all.net" "+*.all.net/*" -v  

###Html5, W3c y Dom:  

Firebug  
HTML Regex Data Extractor  

##Perl, python, java, php, R...:  



###Scrapy:  

1. Scraping express por Serafín Velez Barrera

![scrapy](/images/scrapy.png)

2. Scraping Web Pages with Scrapy - YouTube

  
##2. Scraping para no programadores.  
  
###Google spreadsheet:  

1. ImportHTML()  
2. importxml()  

###Google refine: 

Open refine  

![OpenRefine](/images/OpenRefine.png)

http://openrefine.org/ 

##3. Extracción de datos en PDFs. 
  
###Tabula:  
  1. Java.
  ![tabula_1](/images/No_tengo_java.png)  
  ![tabula_1](/images/java.png)  

  2. Tabula. 
  http://tabula.technology/ 
![tabula_1](/images/tabula_1.png)
![tabula_1](/images/tabula_2.png)
![tabula_1](/images/tabula_3.png)
    
##4. Fuentes de datos comunes.  
  
###Data Warehouse. 

1. Data warehaouse  

Es una colección de datos orientados al tema, integrados,
no-volátiles e historiados, organizados para dar soporte a los
procesos de ayuda a la decisión.  

![DataWarehouse_1](/images/DataWarehouse_1.png)
![DataWarehouse_2](/images/DataWarehouse_2.png)

Tipos de usuarios:   

a. Granjero  
- Accede a información de forma predecible y repetitiva.  
- Sólo accede a su parcela de información: extrae datos para mejorar el funcionamiento de la empresa.
- Utiliza herramientas OLAP. 

b. Explorador  
- Explora gran cantidad de datos.  
- Accede a información de forma impredecible e irregular.  
- Perfil informático o estadístico.  
- Objetivo: Obtener información que proporcione ventaja competitiva.  

c. Turista  
- Grupo de dos o más personas.  
- Un perfil con conocimientos del negocio y visión global empresa.  
- Segundo perfil con conocimientos informáticos.  
- Consulta datos y metadatos.  
- Acceden sin ningún patrón de acceso.  
- Las herramientas que utiliza suelen ser navegadores o buscadores.  
- Su resultado serán proyectos para los usuarios granjero y explorador.  

2. Pentaho  

http://es.wikipedia.org/wiki/Pentaho  

![pentaho](/images/pentaho_1.png)
![pentaho](/images/Pentaho_2.png)

###Problema codificación.   
http://es.wikipedia.org/wiki/Codificaci%C3%B3n_de_caracteres  
![Codificacion](/images/Codificacion.png)  



  




