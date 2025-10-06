# Portafolio

Se trata de un portafolio hecho con Angular (StandAlone).
Hay diferentes secciones y entre ellas está el de "projects".
Donde he añadido los dos proyectos principales backends que tengo y un proyecto de empresa.

Para generar build para producción en la carpeta docs. 
Hay que usar el siguiente comando:
cd mi-portafolio
ng build --configuration production --output-path ../docs --base-href /Portafolio/
Siendo así "Portafolio" el nombre del repsitorio.

Una vez ejecutado, se generará en docs, una carpeta browser, hay que sacar el contenido de browser a docs.