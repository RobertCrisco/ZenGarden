# ZenGarden
@use "variables" as *; //this puts all the variables in the global namespace.
//Default Colors
$color-white:    #fff;
$color-black:    #000;
//Theme Colors
$color-brown:  #483434;
$color-blue: #22577A;
$color-greenDark: #2A8C4A;
$color-greenMed: #64C27B;
$color-greenLit: #D0FDD7;

$background-body:#fdb4eb;
//Theme Fonts
$font-header: Helvetica, "Gills Sans", "Trebuchet MS";
$font-body: Didot, "Bodoni MT", "Palatino";

//Especific Fonts

$font-helv: Helvetica;
$font-gill: "Gill Sans";
$font-treb: "Trebuchet MS";
$font-didot: "didot";
$font-bondo: "bondoni MT";
$font-pala: "palatino";

//@mixin  zone.

@mixin size-p {
  font-weight: normal;
  font-size: 1em;
  line-height: normal;
}

@mixin a {
  font-weight: normal;
  font-size: 1em;
  line-height: normal;
  text-decoration: none;
}

@use 'atoms';
@use 'molecules';
@use 'organisms' as o;

* {
  
    
}

html {
    padding: 0;
  
}

body {
    padding: 0;
    background-color:$background-body;
}

p{
    color:$color-greenDark;

}
