```
Funcion resultado <- distanciacomparada (boolean)
	
	Definir resultado Como Logico;
	Definir numnegativo, numpositivo Como Real;
	numnegativo = 0;
	numpositivo = 0;
	
	Para contador=1 Hasta 5 Con Paso 1 Hacer
		Escribir "Ingresa un numero"
		leer num
		SI num > 0 Entonces
			numpositivo = numnegativo + num;
		SiNo
			numnegativo = numnegativo + num;
		FinSi
	FinPara
	
	resultado = numpositivo > Abs(numnegativo)
Fin Funcion

Algoritmo Distancia_Comparada
	Imprimir distanciacomparada(boolean)
FinAlgoritmo
```
