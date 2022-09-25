<!DOCTYPE html>
<html>
<head>
   <meta Charset="UTF-8">
   <meta name="viewport" content="width=device-width", initial-scale="1">
   <link rel="stylesheet" href= "style.css">
   <title> module2 solution houda </title>
   <style>
   *{
    box-sizing: border-box;
    }



    h1 {
     margin-bottom: 40px;
     text-align: center;
     font-family: sans-serif;
     font-size: 175%;
     margin-top: 40px;
     font-weight: bold;
      }
       
    section {
     position: relative;
     padding: 15px;
     width: 100%;
     }
    

    p {
     position: relative;
     clear: right;

     }

    div {

     position: relative;
     margin-right: auto;
     margin-left: auto;
     margin-bottom: auto;
     background-color: #757474;
     border: 1px solid black;
     width: 100%;
  
     }
    
     .chiken { 

     float: right;
     color: yellow;
     background-color:#D21414;
     border: 1px solid black;
     padding: 5px; 
     width: 100px;
     font-size: 125%;
     text-align: center;
     margin: 0px;
     font-weight: bold;

      }
 

     .beef {
 
     float: right;
     color: white;
     background-color:#165505;
     border: 1px solid black;
     padding: 5px;
     width: 100px;
     font-size: 125%;
     text-align: center;
     margin: 0px;
     font-weight: bold;
 
     }

     .sushi {
 
     float: right;
     color: black;
     background-color:#AD229B;
     border: 1px solid black;
     padding: 5px; 
     width: 100px;
     font-size: 125%;
     text-align: center;
     margin: 0px;
     font-weight: bold;

     }

     .paragraph{
     padding: 5px;
     height: 150px;
     margin:0px;
     font-family: sans-serif;
     overflow: auto;
     border: none;
     }



   /*desktop view*/

   @media (min-width: 992px) {
       .col-lg-4 {
         float: left;
         width: 33.33%;
         margin-right: auto;
         margin-left: auto;

      } 
     } 

   /* tablet view */

   @media (min-width: 768px) and (max-width: 991px) {
        .col-md-6 {
        float:left;
        width: 50%;   
        margin-right: auto;
        margin-left: auto;

      }

        .col-md-12 {
        float: left;
        width: 100%;   
        margin-right: auto;
        margin-left: auto;

      }
    }   
         


     /* mobile view*/  
    @media (max-width: 767px) {
        .col-sm-12 {
            float: left;
            width: 100%;

        }
    }
</style>
 </head>
 
 <body>
 	<h1> Our Menu </h1>

    
   	<section class= "col-lg-4 col-md-6 col-sm-12">
   	 	
   	 	<div> 
   	 		  <p class="chiken">Chiken</p>
   	 		  <p class="paragraph"> 
   	 		  Le lorem ipsum est, en imprimerie, une suite de mots sans signification utilisée à titre provisoire pour calibrer une mise en page,
   	 		  le texte définitif venant remplacer le faux-texte dès qu'il est prêt ou que la mise en page est achevée. 
   	 		  Généralement, on utilise un texte en faux latin, le Lorem ipsum ou Lipsum. </p> 
   	 		  
   	 		 
   	 	 </div>
   	 	 </section>

   	<section class= "col-lg-4 col-md-6 col-sm-12">

   	 	<div>
   	 		   <p class="beef">Beef</P>
   	 		  <p class="paragraph">
   	 		  Le lorem ipsum est, en imprimerie, une suite de mots sans signification utilisée à titre provisoire pour calibrer une mise en page, 
   	 		  le texte définitif venant remplacer le faux-texte dès qu'il est prêt ou que la mise en page est achevée. Généralement,
   	 		  on utilise un texte en faux latin, le Lorem ipsum ou Lipsum. </p> 

   	 		
   	 	</div>
        </section>
   	 	

     <section class= "col-lg-4 col-md-12 col-sm-12">

        <div> 
        	  <p class="sushi"> Sushi </p> 
              <p class="paragraph"> 
              Le lorem ipsum est, en imprimerie, une suite de mots sans signification utilisée à titre provisoire pour calibrer une mise en page, 
              le texte définitif venant remplacer le faux-texte dès qu'il est prêt ou que la mise en page est achevée. 
              Généralement, on utilise un texte en faux latin, le Lorem ipsum ou Lipsum.</p> 


          </div>
          </section>  
