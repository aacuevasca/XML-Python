# README

## XLT
XSLT (eXtensible Stylesheet Language Transformations) és un llenguatge per transformar documents XML en altres documents XML o en altres tipus de documents com ara HTML, text pla o en format XSL-FO (que després pot ser convertit a PDF, PostScript i/o PNG)
Normalment, els documents d'entrada són arxius XML, però també poden ser altres tipus de formats. El document d'entrada no es canvia, sinó que un nou document es crea basant-se en el contingut d'un ja existent.
Hi ha processadors de XSLT en llenguatges com C, C++, Java, Python, Perl, Javascript.
Els navegador webs més habituals (Safari, Chrome, Firefox, microsoft Edge, Opera,...) porten un processador de XSLT incorporat.

![imagen_2024-04-03_185957219](https://hackmd.io/_uploads/rJGfiWoJ0.png)

Hi ha processadors de XSLT en llenguatges com C, C++, Java, Python, Perl, Javascript.
Els navegador webs més habituals (Safari, Chrome, Firefox, microsoft Edge, Opera,...) porten un processador de XSLT incorporat.

## XPATH
XPath (XML Path Language) es un lenguaje utilizado para navegar y seleccionar partes específicas de un documento XML. Es similar a un lenguaje de consulta que permite identificar elementos y atributos en un documento XML mediante la especificación de rutas o ubicaciones.

- ### Node arrel
El node arrel en un document XML és el punt de partida o el nivell superior del document. És el primer node en la jerarquia del document i conté a tot el document XML com a fill. Aquest node arrel és representat per una sola etiqueta que engloba tot el contingut del document XML. És el punt d'entrada per a tota la navegació i consulta dins del document XML. En XPath, el node arrel és representat per una barra inclinada `/`.

- ### Elements
En XPath, els elements són els components bàsics d'un document XML i es poden seleccionar utilitzant expressions de ruta. Per seleccionar un element específic en XPath, es pot utilitzar la seva etiqueta o el seu nom.

Per exemple, si volem seleccionar tots els elements ***llibre*** d'un document XML, podem utilitzar la següent expressió XPath:

```
//llibre
```

- ### Atributs
En XPath, els atributs es refereixen amb l'@ seguit del nom de l'atribut. Per exemple, si volem seleccionar el valor de l'atribut id d'un element ***persona***, utilitzaríem la següent expressió XPath:

``` xpath
/persona/@id
```

- ### Text

Els textos es refereixen al contingut de text que es troba dins dels elements d'un document XML. Per accedir a aquests textos, es pot utilitzar la funció text(). Per exemple, si volem seleccionar el text dins d'un element ***nom*** d'un document XML, podem utilitzar la següent expressió XPath:

``` xpath
//nom/text()
```
    
## DOM
xml.dom.minidom, o DOM, és una implementació mínima de la interfície Document Object Model (Model d'objectes del document), amb una API similar a la d'altres llenguatges. Està destinada a ser més simple que una implementació completa del DOM i també significativament més petita. Aquells usuaris que encara no dominin el DOM haurien de considerar utilitzar el mòdul xml.etree.ElementTree en el seu lloc per al seu processament XML.

#### Tipus d'objectes
- DOMImplementation
- Node
- NodeList
- DocumentType
- Document
- Element
- Attr
- Comment
- Text
- ProcessingInstruction

Per mes informació:
[xml.dom.minidom — Implementación mínima del DOM](https://docs.python.org/es/3/library/xml.dom.minidom.html)
[xml.dom — The Document Object Model API](https://docs.python.org/3/library/xml.dom.html)

## Python
Python és un llenguatge de programació de propòsit general àmpliament utilitzat en diversos àmbits com el desenvolupament de programari, la ciència de dades, la intel·ligència artificial, el desenvolupament web i molts altres. És conegut per la seva sintaxi clara i llegible, el que facilita la seva comprensió i aprenentatge per als programadors novells.

``` py
colors = ["vermell", "blau", "verd", "groc", "taronja"]

print("Llistat de colors:")
for color in colors:
    print(color)
```
