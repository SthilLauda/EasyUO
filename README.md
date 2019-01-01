# EasyUO
Colección de archivos relacionados con EasyUO, con fines variados.

1.) Resaltado de sintaxis para EasyUO en el editor de texto "Sublime Text":

Instalación:

- Ir al directorio "Packages" de Sublime Text: Preferences -> Browse Packages
- Crear el directorio o carpeta "EasyUO"
- Copiar los dos ficheros en el nuevo directorio EasyUO, de tal forma que quede \Sublime Text 3\Packages\EasyUO\

EasyUO.tmLanguage
EasyUO.YAML-tmLanguage

Por alguna razón, el reconocimiento no es ignorecase, de modo que he cambiado la expresión regular para que también resalte
en caso de estar en mayúsculas, por ejemplo al escribir #FINDITEM, etc.

Para ello puedes copiar este tercer fichero junto a los otros dos:

EasyUO.sublime-syntax

- FIN. La nueva opción para la sintaxis de EasyUO estará disponible en: View -> Syntax -> EasyUO
