harjutus-3
==========
<!DOCTYPE HTML>
<html>
   <head>
   <title>Harjutus3</title>
   <meta http-equiv="Content-Type" content="text/html;
   charset=utf-8">
   <title>PHP põhitõed</title>
   </head>
   <body>
    <h1>Muutujad</h1>
      <?php 
          $variable = 10;
          echo $variable;
          echo "<br>";
       ?>  

       <?php 
          $variable = 20;
          echo $variable;
       ?> 
       <h1>Stringid</h1>
       <?php echo " Hello world"; 
       echo "<br>";
       echo ' Hello world'; 
       echo "<br>";

          $text = 24;
          $text2 = 26;
          echo $text . $text2; 
          echo "<br>";
       ?>
       <h2>Nimekirja väljastamine muutujate ja stringide abil</h2>
       <?php
          $student1 = "Risto";
          $student2 = "Maile";
          $student3 = "Tõnis";
          $student4 = "Ants";
          $student5 = "Margit";

          echo 
         "<ul>
              <li>".$student1."</li>
              <li> ".$student2."</li>
              <li> ".$student3."</li>
              <li> ".$student4."</li>
              <li> ".$student5."</li>
          </ul>" ; 
          
          $firstName = "Aile";
          $lastName = "Orgla";
          $fullName = "$firstName " . "$lastName";
          echo "$fullName" ;  
          echo "<br>";
    

   </body>

</html>
