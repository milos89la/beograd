# beograd
beograd

function mixer($rec1,$rec2)
   {
    $dodato=0;

      for($i=0;$i<strlen($rec1);$i++){
        if($i<strlen ($rec2)-1){
            echo $rec1[$i].$rec2[$i];
            

        }
        else{
            echo $rec1[$i];
        }
       $dodato++;
      }
      for($i=$dodato;$i<strlen($rec2);$i++){
        echo $rec2[$i];

      }


   }
mixer("beo","grad");
