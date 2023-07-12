<!DOCTYPE html>
<html>
    <link rel="stylesheet" href="style.css" />
    <head>
        <meta charset="UTF-8" />
        <title>Portfolio</title>
        <style>
            #profile{
                border-radius: 100px;
                border: 5px solid #F3AA60;
            }
            .title{
                padding: 0px;
                font-size: 25px;
                text-align: center;
            }
            .container{
                display: flex;
                flex-direction: column;
                align-items: center;
                font-size: 30px;
            }
            p > a{
               color: black;
               font-weight: 700;
          }
        </style>
    </head>
    <body style="background-color: #EF6262;">
        <div class="title">
            <img id="profile" height="200px" src="./vedant.png" alt="image of vedant" />
              <h2>Vedant Salvi</h2>        
            </div>
        <div class="container">
            <div class="Project">
               <p><a href="./project.html">Project</a></p>
            </div>
            <div class="About_me">
               <p> <a href="./about.html" > About Me </a></p>
            </div>
            <div class="Contact_me">
            <p> <a href="./contact.html">Contact</a></p>
            </div>
        </div>
 </body>

</html>
