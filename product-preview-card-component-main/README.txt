Montserrat Variable Font
========================

This download contains Montserrat as both variable fonts and static fonts.

Montserrat is a variable font with this axis:
  wght

This means all the styles are contained in these files:
  Montserrat-VariableFont_wght.ttf
  Montserrat-Italic-VariableFont_wght.ttf

If your app fully supports variable fonts, you can now pick intermediate styles
that aren’t available as static fonts. Not all apps support variable fonts, and
in those cases you can use the static font files for Montserrat:
  static/Montserrat-Thin.ttf
  static/Montserrat-ExtraLight.ttf
  static/Montserrat-Light.ttf
  static/Montserrat-Regular.ttf
  static/Montserrat-Medium.ttf
  static/Montserrat-SemiBold.ttf
  static/Montserrat-Bold.ttf
  static/Montserrat-ExtraBold.ttf
  static/Montserrat-Black.ttf
  static/Montserrat-ThinItalic.ttf
  static/Montserrat-ExtraLightItalic.ttf
  static/Montserrat-LightItalic.ttf
  static/Montserrat-Italic.ttf
  static/Montserrat-MediumItalic.ttf
  static/Montserrat-SemiBoldItalic.ttf
  static/Montserrat-BoldItalic.ttf
  static/Montserrat-ExtraBoldItalic.ttf
  static/Montserrat-BlackItalic.ttf

Get started
-----------

1. Install the font files you want to use

2. Use your app's font picker to view the font family and all the
available styles

Learn more about variable fonts
-------------------------------

  https://developers.google.com/web/fundamentals/design-and-ux/typography/variable-fonts
  https://variablefonts.typenetwork.com
  https://medium.com/variable-fonts

In desktop apps

  https://theblog.adobe.com/can-variable-fonts-illustrator-cc
  https://helpx.adobe.com/nz/photoshop/using/fonts.html#variable_fonts

Online

  https://developers.google.com/fonts/docs/getting_started
  https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Fonts/Variable_Fonts_Guide
  https://developer.microsoft.com/en-us/microsoft-edge/testdrive/demos/variable-fonts

Installing fonts

  MacOS: https://support.apple.com/en-us/HT201749
  Linux: https://www.google.com/search?q=how+to+install+a+font+on+gnu%2Blinux
  Windows: https://support.microsoft.com/en-us/help/314960/how-to-install-or-remove-a-font-in-windows

Android Apps

  https://developers.google.com/fonts/docs/android
  https://developer.android.com/guide/topics/ui/look-and-feel/downloadable-fonts

License
-------
Please read the full license text (OFL.txt) to understand the permissions,
restrictions and requirements for usage, redistribution, and modification.

You can use them in your products & projects – print or digital,
commercial or otherwise.

This isn't legal advice, please consider consulting a lawyer and see the full
license for all details.
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> 

  <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">
  
  <title>Frontend Mentor | Product preview card component</title>
 <style>
  
 @font-face{
font-family: 'Montserrat';
src: url('fonts/Montserrat-VariableFont_wght.ttf') format('truetype');
}
@font-face {
  font-family: "Fraunces";
  src: url('fonts/Fraunces-VariableFont_SOFT\,WONK\,opsz\,wght.ttf') format('truetype');}
@media(max-width:800px){
div{


}
.imagem{
height: 300px;
width:300px;
background-color: aqua;
position: relative;

}
.conteudo{
  height: 300px;
  width:300px;
  position: absolute;
  font-size: 0.7em;
  bottom: 0px;
   }

 






}
 





body {
background-color: hsl(30, 38%, 92%) ; 
height: 100vh;
width: 100vw;
padding: 0px;
margin: 0px;
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
}
p{
font-size: 14px;
font-family: 'Fraunces';
text-align: justify;
}
h1{
  font-family: 'Fraunces';
  font-size: 1.8em;
}
h2{
 font-family: 'Montserrat'; 
 font-size: small;
 font-weight: lighter;
}

div{
width: 265px;
height: 400px;
display: inline-block;

}




.imagem{
position: relative;
float: left;
border-top-left-radius:10px ;
border-bottom-left-radius: 10px;
background-color: aqua;

}
.imagem img {
  width: 100%;
  
  
}



.conteudo{
background-color: white;
padding: 10px 20px 20px 20px;
margin: 0px;
box-sizing: border-box;
border-top-right-radius: 10px;
border-bottom-right-radius: 10px;
}
.conteudo ul{display: flex;
}
.conteudo ul li {
list-style-type: none;
padding-right: 20px;
color:hsl(158, 36%, 37%) ;
font-size: 1.0em;
font-family: 'Fraunces';
}
 #oferta{
  font-size: x-large;
  font-weight: bolder;
}
#preço{
text-decoration: line-through;
}

button {
  font-family: 'Montserrat';
  border-radius: 5px;
  width: 210px;
  height: 40px;
  background-color:hsl(158, 36%, 37%) ;
  margin-top: 10px;
  text-align: center;
  color: white;
  }


</style>
  
</head>

<body>
  
  

<div class="imagem" >
 <picture>
  <source media="(max-width: 800px)" srcset="images/image-product-mobile.jpg">
  <img src="images/image-product-desktop.jpg" alt="desktop">
</picture>
 
</div>
<div class="conteudo" >
  <h2>PERFUME</h2>
        
  <h1>Gabrielle Essence Eau De Parfum</h1>
   <p>
    A floral, solar and voluptuous interpretation composed by Olivier Polge, 
    Perfumer-Creator for the House of CHANEL.   </p> 
   <ul>
<li id="oferta">$149.99</li>
<li id="preço">$169.99</li>
   </ul>
    <button>
    <img src="images/icon-cart.svg" alt="#">
    Add to Chart
    </button>
    
    
 </div>
 


         
      
      
    
  

 
  
 
  
</body>
</html>