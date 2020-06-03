---
title: Home
---
<html>
 <head>
  </head>
  <body>
   <style>
   .item1 {background: white;}
  
   .item2 {background: white;}
  
   .item3 {background: white;}
  
   .item4{background: white;}
  
   .container { 
     font-size:20px;
     min-height:300px
     width: 100%;
     background: white;
     display: grid;
     grid-template-columns: 1fr 1fr;
     grid-template-rows: 1fr 1fr;
     grid-gap:10px;
     text-align: center;
   }
 .image 
   { 
   position: relative; /* To help the image + text element to get along with the rest of the page*/ 
   width: 100%; /* for IE 6 */ 
   } 
   h2 
   { 
   position: absolute; /* To place the text on the image*/
   top: 200px; /* The exact location of the text from the top of the image*/
   left: 0; /* Other beautification stuff */
   width: 100%; 
   }
   /* Coloring time */
   h2 span /* decorating the text within the span tag */
   { 
   color: white; 
   font: bold 24px/45px Helvetica, Sans-Serif; 
   letter-spacing: -1px; 
   background: rgb(0, 0, 0); /* fallback color */ 
   background: rgba(0, 0, 0, 0.7); padding: 10px; 
   }
   h2 span.spacer { padding:0 5px; } /* to pad the background color of text to make it look more elegant */
 </style>
    <div class="image"> <!-- the image container -->
     <img src="assets/img/hero/Montreaux.jpeg" alt="" /> <!-- the image -->
     <h2>
     <span>A Movie in the Park:<span class='spacer'></span><br /><span class='spacer'></span>Kung Fu Panda</span> <!-- span tag to beautify it efficiently -->
     </h2> <!-- the text -->
     </div>
    <h1 align="center">Edward Southerington</h1>
    <p style="color: blue" align="center">MSc in Economics Graduate, Nova School of Business and Economics</p>
    <p style="color: blue" align="center">Bachelor of Laws / Bachelor of Business Under-graduate, La Trobe University</p>
    <h1 align="center">Data Analysis Portfolio</h1>
 
  <div class="container">
   <div class="item1">Python Projects</div>
   <div class="item2">R Projects</div>
   <div class="item3">Python Projects.....</div>
   <div class="item3">R Projects.....</div>
  </div>
  
 </body>
</html>
  
  
