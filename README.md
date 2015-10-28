# Lista_WEB

1.

var x='Churros';


function Imprime(y){
var r=y.substring(0,4);
 alert(r);
       }
    
    Imprime(x);
    
 2.

    var x=['Salvador','São Paulo','Rio de Janeiro','Tocantins'];
    
    function City(y){
     
    var i=y.length;
    var g,t;
     var z=[''];
       for(g=0;g<i;g++){
         
         t=y[g];
         
         if(t[0]=='S'||t[0]=='s'){
             z.push(y[g]);
         }
         
         }
          alert(z);
    }
    
    City(x);
