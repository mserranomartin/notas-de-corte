# Histórico de las notas de corte de España
Evolución de las notas de corte en todas las universidades públicas de España desde 2010 hasta 2021

### Bases de datos
Las notas de corte se han extraído de distintos lugares según la Comunidad Autónoma. Ha sido una labor trabajosa de extraer y aunar los datos, que normalmente estaban en PDF. Para pasarlos a CSV se ha usado el programa [Tabula](https://tabula.technology/). En concreto, los datos de las notas de corte se han cogido de acuerdo según la comunidad de: 

- **Madrid:** la [página web de la UC3M](https://www.uc3m.es/admision/notas-corte) que conserva en formato .pdf las publicaciones de todas las notas de corte desde el curso 2007/2008.
- **Cataluña:** 

### Gráficos
Los gráficos de las notas se han creado en R con la libreria `ggplot2`. Se pueden ver los gráficos de forma más cómoda en [esta página](https://homomorfismo.github.io/historico_notas_madrid/).

### Página web
Aunque sería más apropiado usar una base de datos, la página web del apartado anterior funciona enteramente con Javascript para poder alojarla en GitHub Pages. Está construida usando [Bootstrap](https://getbootstrap.com/) por la facilidad que da.
