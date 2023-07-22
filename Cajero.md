```
Funcion saldo <- cashier (cantidad)
	Definir saldo Como Real;
	saldo = 1000;
	Repetir
		Imprimir Mayusculas("--- Selecciona una opción: ---") ;
		Imprimir "a. Depositar ";
		Imprimir "b. Retirar ";
		Imprimir "c. Salir ";
		Leer posibilidad
		Si posibilidad = "a" Entonces
			saldo = saldo + deposito(cantidad)
		FinSi
		Si posibilidad = "b" Entonces
			saldo = saldo - retiro(cantidad)
		FinSi
	Mientras Que posibilidad = "a" | posibilidad = "b"
Fin Funcion

Funcion cantidad <- deposito(cantidad)
	Imprimir "¿Cuánto deseas depositar?:";
	leer cantidad
FinFuncion

Funcion cantidad <- retiro(cantidad)
	Imprimir "¿Cuánto deseas retirar?:";
	Leer cantidad
FinFuncion

Algoritmo Cajero
	Imprimir cashier(cantidad)
FinAlgoritmo
```
