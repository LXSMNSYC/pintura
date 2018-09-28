# pintura
Color Helper Classes for CSS
## How to use?
### Import
Since there are 4 properties that accepts color values (except the border specificity.), I decided to split the files into those properties.
The files include:
* ```<design class>```-bg
* ```<design class>```-border 
* ```<design class>```-outline
* ```<design class>```-text

Import one of those files:
```html
<link rel="stylesheet" href="/path/to/pintura.<design-class>-<property>.min.css>
```
Example:
Imports the Material Design palette for background
```html
<link rel="stylesheet" href="/path/to/pintura.md-bg.min.css>
```

### Using the classes
Pintura is an OOCSS, each values can be stated seperately.

Template:
```html
<div class="<design-class> <color> <grade>">

</div>
```
```<design-class>``` is the abbreviaton for the design systems available. 
```<color>``` represents the equivalent word for the color provided by the design-class
```<grade>``` represents the value provided for the color, prefixed with "G". 

Example:
```html
<div class="md red G500">
I have some neat background.
</div>
```