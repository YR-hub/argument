// Ejercicio con if
let numeroIf = 5;

class Argumentos {
	public static void main(String[] args){
		System.out.println("Numeros");
	}

}

if (numeroIf > 0) {
  console.log("El número es positivo");
} else if (numeroIf < 0) {
  console.log("El número es negativo");
} else {
  console.log("El número es 0");
}

// Ejercicio con while
let numeroWhile = 0;

while (numeroWhile < 3) {
  numeroWhile++;
  console.log(numeroWhile);
}

// Ejercicio con do while
let numeroDoWhile = 0;

do {
  numeroDoWhile++;
  console.log(numeroDoWhile);
} while (numeroDoWhile < 3);

// Ejercicio con for
for (let numeroFor = 0; numeroFor <= 3; numeroFor++) {
  console.log(numeroFor);
}

// Ejercicio con switch
let estacion = "verano";

switch (estacion) {
  case "invierno":
    console.log("Estamos en invierno");
    break;
  case "primavera":
    console.log("Estamos en primavera");
    break;
  case "verano":
    console.log("Estamos en verano");
    break;
  case "otoño":
    console.log("Estamos en otoño");
    break;
 
