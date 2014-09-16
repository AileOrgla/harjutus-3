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
    
         $test = "Testin";
          echo "$test kas interpolatsioon töötab";
          echo "<br>";

         $age = "20";
          echo "Ma olen {$age}aastane";

          $source = "see Tekst SISALDAB suuri TÄHEMÄRKE!!!";
          $lower = strtolower($source);
          echo "<p>{$lower}</p>";

          $source = "see Tekst SISALDAB suuri TÄHEMÄRKE!!!";
          $upper = strtoupper($source);
          echo "<p>{$upper}</p>";

          $source = "see Tekst sisaldab suuri tähemärke!!!";
          $first = ucfirst($source);
          echo "<p>{$first}</p>";

          $source = "see Tekst sisaldab suuri tähemärke!!!";
          $words = ucwords($source);
          echo "<p>{$words}</p>";

          $source = "see Tekst sisaldab suuri tähemärke!!!";
          $strlen = strlen($source);
          echo "<p>{$strlen}</p>";

          echo "A" . trim(" B C D E") . "F";
      ?>
    <h2>Täisarvud</h2>
       <?php 
          $nr1 = 5;
          $nr2 = 10;
          echo ($nr1 + $nr2) * 2;
          echo "<br>";

          echo abs(-300);
          echo "<br>";
          // Viis ruudus:
          echo pow(5, 2);
          echo "<br>";
          // Seitse kuubis:
          echo pow(7, 3);
          echo "<br>";
          // Kolm astmel seitse:
          echo pow(3, 7);
          echo "<br>";

          // Ruutjuur 25-st:
          echo sqrt(25);

          // Suvaline number
          echo rand();

          // Lihtsalt reavahetus, et vältida segadust piiranguteta ja piiranguga numbritel vahet tegemisel.
           echo "<br>";

          // Suvaline number vahemikus 7 - 22:
          echo rand(7, 22);
   </body>

</html>
