# Riderly-hiring-test
***

## English

### Requirements
1. It is required to code the UI for the Figma file, using html and css or sass/scss.
2. The UI needs to be responsive and adapt to the dimensions of any screen/browser.
3. The UI design for the mobile version is not provided, use your criteria in order to implement it.
4. You can use any external css and js libraries you may need.
5. Using Bootstrap to implement the layout of the site is preferred. We also encourage the use of Flexbox.
6. The font used in the site design is "Roboto" and it is requested to import it from Google fonts (https://fonts.google.com/)

<h3 align="center">Figma</h3>
<p align="center"><img src="https://i.ibb.co/pRWvFYQ/Riderly-Overview-Section.png" alt="Riderly-Overview-Section" border="0"></p>

### Implemented technologies
- HTML
- CSS
- Bootstrap

### Fonts
- Roboto ( https://fonts.google.com/ )
- Russo One ( https://fonts.google.com/ )

### Process
***
The implementation was done in html, working with the Bootstrap grid system. This implementation system was chosen due to its ease of use when working with different screen sizes. 

The font Roboto in size 14px was assigned to the whole document as it is the one found in the figma file, (with exception of the logo for obvious reasons). This ensures that if the loading of any specific font fails there will be a backup, where the whole document will display text using the same font. 

There is presence of different colours and sizes within the used typography, so these specific styles were assigned using css.  

- **Header**

In the header, all the subcomponents were included in a collapsible navigation bar selected for screen sizes smaller than 990px.
The logo of the company was not included in this system, and works with its z-index, so its position will always be centered in relation to the screen no matter the size of it. 

- **Recent invoices**

The recent invoices component was also made using the Bootstrap grid system, making use of “container”, “row” and “col” so as to give the design breakpoints to modify the number of columns that each value occupies in the table. 

- **Settings**

In the same way for the “Settings” component, three cards were generated (“Profile”, “Shipping”, “Payment”) each of these take up three columns in screens bigger than 767px, and in smaller ones they take up twelve columns for a better visualization.

- **Footer**

The Footer was structured into two “containers” that take up six columns in screens bigger than 767px, and in smaller ones they take up twelve columns, not only for a better visualization in small devices but also to provide a better user interaction with the links and buttons existing in the document. 
***

## Español

### Consigna
1. Se requiere codificar la interfaz de usuario para el archivo Figma, usando html y css o sass / scss.
2. La interfaz de usuario debe responder y adaptarse a las dimensiones de cualquier pantalla / navegador.
3. No se proporciona el diseño de la interfaz de usuario para la versión móvil, utilice sus criterios para implementarlo.
4. Puede usar cualquier biblioteca externa de CSS y JS que necesite.
5. Se prefiere usar Bootstrap para implementar el diseño del sitio. También fomentamos el uso de Flexbox.
6. La fuente utilizada en el diseño del sitio es "Roboto" y se solicita importarla desde fuentes de Google 

<h3 align="center"> Archivo figma</h3>
<p align="center"><img src="https://i.ibb.co/pRWvFYQ/Riderly-Overview-Section.png" alt="Riderly-Overview-Section" border="0"></p>


### Tecnologías utilizadas
- HTML
- CSS
- Bootstrap
##

### Fuentes online
- Roboto ( https://fonts.google.com/ )
- Russo One ( https://fonts.google.com/ )
##

### Proceso de implementación
***
La implementación fue realizada en html, trabajando con el sistema de grilla de Bootstrap. Este sistema de implementación fue elegido por su practicidad a la hora de trabajar con distintos tamaños de pantalla.

Se adjudicó la fuente “Roboto” con tamaño 14px a la totalidad del documento ya que es el estilo encontrado en el archivo figma (con excepción del logo por obvias razones). De esta forma se asegura que si ocurre alguna falla en la carga de alguna fuente específica tendremos como respaldo la uniformidad en el texto.

Tenemos la presencia de distintos tamaños y colores dentro de la tipografía utilizada, por lo que se adjudicaron estilos específicos mediante css.

- **Header**

Para el “Header” se optó por incluir todos los subcomponentes en una barra de navegación colapsable para pantallas de tamaños menores a 990px.
El logo de la empresa se dejó por fuera de este sistema, trabajando con su z-index para que su posición siempre esté centrada en referencia a la pantalla sin importar el tamaño de esta. 


- **Recent Invoices**

El componente “Recent Invoices” también se trabajó con el sistema de grilla de Bootstrap, utilizando “container”, “row” y “col” para de esta forma marcar puntos de quiebre y modificar la cantidad de columnas que ocupa cada dato de la tabla.


- **Settings**

De la misma forma para el componente “Settings” se generan tres “cards” (“Profile”, “Shipping”, “Payment”), cada una de éstas ocupa tres columnas en pantallas mayores a 767px y en menores, doce columnas para una mejor visualización.


- **Footer**

El “Footer” se estructuró en dos “containers” que ocupan seis columnas en pantallas mayores a 767px y en menores ocupan 12 columnas, no solo para otorgar una mejor visualización en pequeñas dispositivos sino también para proveer una mejor interacción del usuario con los links y botones que existen en el documento.




