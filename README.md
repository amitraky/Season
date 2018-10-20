# Season
The some specel points

# Random 6-digit number create 

  ``` 
  function rands($number=6){
      $characters =  'abcdefghijklmnopqrstuvwxyz0123456789';
      $string = '';
      $max = strlen($characters) - 1;
      for ($i = 0; $i < $number; $i++) {
        $string .= $characters[mt_rand(0, $max)];
      }
      return $string;
   }
 ```
