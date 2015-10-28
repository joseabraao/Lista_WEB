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
    
  4.
 
 <!DOCTYPE html>
<html>
<head>
	<title>Div em movimento</title>
	<link rel="stylesheet" type="text/css" href="q3.css" /> 
</head>
<body>
<div id="box"></div>



<script type="text/javascript">

		var left=100;

			setInterval(function () {
			var div = document.getElementById('box');
			div.style.left=left+'px';
			div.style.top=left+'px';
			left=left+100;
			//if (left>500) {left=0};
			}, 10);

	
		</script>
</body>
</html>


5.

    var nome='Jose',sobrenome='Abraao',salario='1999';
    
    
 function Empregado(nome,sobrenome,salario){
    
     this.nome=nome;
     this.sobrenome=sobrenome;
     this.salario_mensal=salario;
     
     function calcularSalarioAno(x){
         x=x*12;
         alert('Salario Anual: '+x);
     }
     
     function dadosEmpregado(nome,sobrenome,salario){
         
         alert(nome+' '+sobrenome+',Salario:'+salario);
         
     }
     
     dadosEmpregado(nome,sobrenome,salario);
     calcularSalarioAno(salario);
 }
    
    Empregado(nome,sobrenome,salario);
    
    
  6.
   
   <!DOCTYPE html>
<html>
<head>
	<title>form</title>
	<link rel="stylesheet" type="text/css" href="q3.css" /> 
</head>
<body>
<h2>Dados:</h2>
<form action="" method="get">
	
	<h3>Nome:</h3>
	<input type="text" name="Nome" required pattern="[a-z\s]+$" /><br>
	<h3>Sobrenome:</h3>
	<input type="text" name="Sobrenome" required pattern="[a-z\s]+$" /><br>
	<h3>Salario:</h3>
	<input type="text" name="salario" required pattern="[0-9]+$" /><br>
	<input type="submit" name="Submit">



</form>



<script type="text/javascript">



	
		</script>
</body>
</html>
@joseabraao
Styling with Markdown is supported
Write Preview

Attach files by dragging & dropping or selecting them.

