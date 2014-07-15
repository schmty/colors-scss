Colors-scss
===========

## Simple sass color variables
(based on mrmrs/colors)

### Installation
with bower
<pre>$ bower install colors-scss --save</pre>
Or simply download <code>https://raw.githubusercontent.com/schmitzjake/colors-scss/master/dist/_colors.scss</code>
to the desired directory.
Then import it in your main.scss (or other .scss) file
```scss
@import 'colors'; // (or path to colors if not in root relative to stylesheet)

body {
  background-color: $red;
  // etc
}
```
