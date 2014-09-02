inteligencia-artificial
=======================
var sandra = [1,2,3,4,5,6];
var num = true
for(var i = 0; i< sandra.length; i++)
{
//var texto = "el numero es impar";
if (sandra[i] % 2 == 0){
	
	texto = "el numero es Par";
	console.log(sandra[i] + "es numero par");
}
else{
	texto = "impar";
	console.log(sandra[i] + "es numero impar");
}
for (var j = 2; j < sandra[i]; j ++){
	if (sandra[i] % j == 0 ){
        num = false;
	}
}

if(num == true )
{
	console.log(sandra[i] + "si es numero primo");
	}
	else{
	console.log(sandra[i] + "No es numero primo");
	}
//console.log(sandra[i] + "es: " + "" texto);	
}
