```
Funcion resultado <- Sumadepares (num)
	Definir resultado Como Real;
	Definir suma Como Real;
	suma = 0;
	
	Repetir
		Escribir "Ingresa un numero entre 1 y 100"
		Leer num
		
		Si  num < 1 O num > 100 Entonces
			Imprimir Mayusculas("Número Inválido")
		SiNo
			Si num % 2 = 0
				suma = suma + num;
			FinSi
		FinSi

	Mientras Que num >= 1  Y num  <= 100
	resultado = suma;
Fin Funcion

Algoritmo Suma_dePares
	Imprimir Sumadepares(num)
FinAlgoritmo
```
