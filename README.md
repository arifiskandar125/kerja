<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS</title>

    <style>
           h1{
            color: blueviolet;
            font-weight: 1000;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
           }

           body{

             background-color: aquamarine;
             background-image: url(https://static.vecteezy.com/system/resources/thumbnails/008/311/935/small/the-illustration-graphic-consists-of-abstract-background-with-a-blue-gradient-dynamic-shapes-composition-eps10-perfect-for-presentation-background-website-landing-page-wallpaper-vector.jpg);
             background-size: cover;
             color: white;
            }




            
     /*Class Selector*/

     .tengah{ text-align: center;
                

            }

            .text-white {

              color:aliceblue;
               }

            .bg-dark{
                    background-color:black;
               
            }

            .content {

              border-color: black;
              border-style: solid;
              margin: 20px 15px 10px;
              padding: 2px 0px 0px 2px;
            }
      /*id selector*/

      #kanan{

           text-align: right;
           text-transform: uppercase;
      }

    </style>

    <link rel="Stylesheet"type="text/css" href="style.css">
</head>
<body>
     <h3>24/02/2025 - intro to CSS</h3>

     <div class="content">

     <h1 class="tengah bg-dark text-white">Welcome to JTMK</h1>
     <h1 id="kanan">Selamat Datang</h1>
     <p style=" color: blue ;font-size: 25px;
     font-family: 'Franklin Gothic Medium', 'Arial Narrow',Arial, Helvetica, sans-serif">intro to CSS</p>
     <p>JTMK Track</p>

     <p>Types of CSS</p>
     <ul>

         <li>Software And Development</li>
         <li>Networking System</li>
         <li>Data Visualization</li>
     </ul>
     </div>
     <h3>footer</h3>
</body>
</html>
