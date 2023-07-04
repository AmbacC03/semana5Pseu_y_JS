```
Funcion resultado <- tiempoConvertido (num)
	Definir resultado Como Caracter;
	Definir dias, horas, minutos, seg Como Entero;
	seg = num % 6;
	minutos = Trunc(num/60) % 60;
	horas = Trunc(num/3600) % 24;
	dias = Trunc(num/86400);
	resultado = Concatenar("Dias: ", ConvertirATexto(dias));
	resultado = Concatenar(resultado, ", Horas: ");
	resultado = Concatenar(resultado, ConvertirATexto(horas));
	resultado = Concatenar(resultado, ", Minutos: ");
	resultado = Concatenar(resultado, ConvertirATexto(minutos));
	resultado = Concatenar(resultado, ", y Segundos: ");
	resultado = Concatenar(resultado, ConvertirATexto(seg));
Fin Funcion

Algoritmo Convertidor_Tiempo
	Imprimir tiempoConvertido(4000)
FinAlgoritmo
```
