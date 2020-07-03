# Format Harga Indonesia Laravel
  
  function format_price_idn($number){ 
    $price =  number_format($number, 0, ',' , '.'); 
    return $price; 
  }
