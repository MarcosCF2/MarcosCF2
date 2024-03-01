main() {
  
  int a = 1;
  int b = 2;
  int c = 8;
  int d = 5;
  int e = 4;
  
  if (( a > b ) && (a > c) && (a > d) && (a > e)) {
    
  print('O maior número é $a');
    
  }

  else {
    
    if (( b > a ) && ( b > c ) && ( b > d ) && ( b > e)) {
      
      print('O maior número é $c');
      
    }
    
    else { 
    
     if (( c > a) && ( c > b ) && ( c > d ) && ( c > e )) {
       
       print ('O maior número é $c');
       
     }
      
      else { 
       
       if (( d > a ) && ( d > b ) && ( d > c ) && ( d > e)) {
         
         print('O maior número é $d');
         
       }
        
        else {
          
          if (( e > a ) && ( e > b ) && ( e > c ) && ( e > d )) {
            
            print('O maior número é $e');
            
         }
  }
}
    }
  }
}
