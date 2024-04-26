# Switch
Pode ser comparada a uma série de instruções if, possuindo uma sintaxe um pouco diferente e usada sobretudo quando se deseja verificar diferentes valores, inúmeras vezes, em uma mesma variável.


<?php

 switch($var1){
	case 10:
		echo "var1 é igual a 10";
	case 20:
		echo "var1 é igual a 20";
		break;
	default:
		echo "var1 não é igual a 10 e nem a 20";
		break;
 }
