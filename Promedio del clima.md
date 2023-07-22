```
Funcion Celsius <- Fahrenheit_ACelsius (Fahrenheit)
	Definir Celsius Como Real;
	Celsius = (Fahrenheit - 32 ) / 1.8
Fin Funcion

Algoritmo Promedio_delClima
	contador = 0;
	total = 0;
	Repetir
		Imprimir Mayusculas("Selecciona una opción: ");
		Imprimir "a. Ingresa los grados en Celsius: ";
		Imprimir "b. Ingresa los grados en Fahrenheit: ";
		Imprimir "x. Salir.";
		Leer posibilidad
		Si posibilidad = "a" O posibilidad = "b" Entonces
			Leer grados
			contador = contador + 1;
		FinSi
		Si posibilidad = "a" Entonces
			total = total + grados;
		FinSi
		Si posibilidad = "b" Entonces
			total = total + Fahrenheit_ACelsius(grados);
		FinSi
	Mientras Que posibilidad = "a" O posibilidad = "b"
	Imprimir total / contador;
FinAlgoritmo
```
