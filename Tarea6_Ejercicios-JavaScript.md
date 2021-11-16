# Tarea 6 Ejercicios JavaScript

A continuación se desarrollarán algunos ejercicios básicos de JavaScript como una forma de practicar y familiarizarse con el lenguaje 8-)

## Ejercicio #1
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/Tarea6_Trabajo_En_Clase_Realizar_Los_Siguientes_20_Ejercicios_En_Javascript/1.png?raw=true)

#### Código
```javascript
var nombre = prompt("Ingrese su nombre")
// Método 1 imprimiendo por variable 
var respuesta =`Ahora estás en la matrix, ${nombre}`
respuesta
// Método 2 imprimiendo por console.log 
console.log(`Ahora estás en la matrix, ${nombre}`)
```

#### Resultado en consola
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio1-1.JPG?raw=true)
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio1.JPG?raw=true)



## Ejercicio #2
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/Tarea6_Trabajo_En_Clase_Realizar_Los_Siguientes_20_Ejercicios_En_Javascript/2.png?raw=true)

#### Código
```javascript
var numero1= prompt("Ingrese un número con decimales")
var numero2= prompt("Ingrese un número entero")
var suma=parseFloat(numero1)+parseFloat(numero2)
// Método 1 imprimiendo por variable 
var resultado= `El resultado de la suma es ${suma}`
resultado
// Método 2 imprimiendo por console.log 
console.log(`El resultado de la suma es ${suma}`)
```

#### Resultado en consola
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio2-1.JPG?raw=true)
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio2-2.JPG?raw=true)
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio2.JPG?raw=true)



## Ejercicio #3
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/Tarea6_Trabajo_En_Clase_Realizar_Los_Siguientes_20_Ejercicios_En_Javascript/3.png?raw=true)

#### Código
```javascript
var numero1= prompt("Ingrese un número")
console.log(`Primer número: ${numero1}`)
var numero2= prompt("Ingrese un segundo número")
console.log(`Segundo número: ${numero2}`)
var suma=parseFloat(numero1)+parseFloat(numero2)
console.log(`Suman: ${suma}`)
var numero3= prompt("Ingrese un tercer número")
console.log(`Tercer número: ${numero3}`)
var multiplicacion=suma*parseFloat(numero3)
console.log(`Multiplicación de la suma por el último número: ${multiplicacion}`)
```

#### Resultado en consola
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio3-1.JPG?raw=true)
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio3-2.JPG?raw=true)
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio3-3.JPG?raw=true)
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio3.JPG?raw=true)



## Ejercicio #4
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/Tarea6_Trabajo_En_Clase_Realizar_Los_Siguientes_20_Ejercicios_En_Javascript/4.png?raw=true)

#### Código
```javascript
var kilometros= prompt("Ingrese la cantidad de kilómetros recorridos por la motocicleta")
console.log(`Kilómetros recorridos: ${kilometros}`)
var combustible= prompt("Ingrese la cantidad de litros de combustible que consumió durante ese recorrido")
console.log(`Litros de combustible gastados: ${combustible}`)
var division=parseFloat(combustible)/parseFloat(kilometros)
console.log(`El consumo por kilómetro es de: ${division}`)
```

#### Resultado en consola
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio4-1.JPG?raw=true)
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio4-2.JPG?raw=true)
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio4.JPG?raw=true)


## Ejercicio #5
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/Tarea6_Trabajo_En_Clase_Realizar_Los_Siguientes_20_Ejercicios_En_Javascript/5.png?raw=true)

#### Código
```javascript
var fahrenheit= prompt("Ingrese una temperatura expresada en grados Fahrenheit")
console.log(`Grados Fahrenheit ingresados: ${fahrenheit}`)
var conversion_celsius= (5/9)*(parseFloat(fahrenheit)-32)
console.log(`El equivalente en grados Celsius de la temperatura ingresada en Fahrenheit es: ${conversion_celsius}`))
```

#### Resultado en consola
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio5-1.JPG?raw=true)
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio5.JPG?raw=true)


## Ejercicio #6
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/Tarea6_Trabajo_En_Clase_Realizar_Los_Siguientes_20_Ejercicios_En_Javascript/6.png?raw=true)

#### Código
```javascript
var numero1= prompt("Ingrese un número")
console.log(`Primer número: ${numero1}`)
var numero2= prompt("Ingrese un segundo número")
console.log(`Segundo número: ${numero2}`)
var numero3= prompt("Ingrese un tercer número")
console.log(`Tercer número: ${numero3}`)
var promedio=(parseFloat(numero1)+parseFloat(numero2)+parseFloat(numero3))/3
console.log(`El promedio de los tres números ingresados es: ${promedio}`)
```

#### Resultado en consola
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio6-1.JPG?raw=true)
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio6-2.JPG?raw=true)
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio6-3.JPG?raw=true)
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio6.JPG?raw=true)


## Ejercicio #7
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/Tarea6_Trabajo_En_Clase_Realizar_Los_Siguientes_20_Ejercicios_En_Javascript/7.png?raw=true)

#### Código
```javascript
var numero1= prompt("Ingrese un número")
console.log(`número ingresado: ${numero1}`)
//Método utilizando concatenación
console.log("Descontando el 15% queda: "+ (numero1-(numero1* 0.15)))
//Método utilizando interpolación
console.log(`Descontando el 15% queda: ${numero1 - numero1*0.15}`)
```

#### Resultado en consola
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio7-1.JPG?raw=true)
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio7.JPG?raw=true)


## Ejercicio #8
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/Tarea6_Trabajo_En_Clase_Realizar_Los_Siguientes_20_Ejercicios_En_Javascript/8.png?raw=true)

#### Código
```javascript
var palabra1= prompt("Ingrese una palabra")
console.log(`Primera palabra ingresada: ${palabra1}`)
var palabra2= prompt("Ingrese otra palabra")
console.log(`Segunda palabra ingresada: ${palabra2}`)
var concatenacion=palabra1+" "+palabra2
concatenacion
```

#### Resultado en consola
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio8-1.JPG?raw=true)
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio8-2.JPG?raw=true)
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio8.JPG?raw=true)


## Ejercicio #9
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/Tarea6_Trabajo_En_Clase_Realizar_Los_Siguientes_20_Ejercicios_En_Javascript/9.png?raw=true)

#### Código
```javascript
var texto= prompt("Ingrese un texto")
//Método utilizando interpolación
console.log(`Texto ingresado: ${texto}`)
console.log(`El caracter en primer lugar es: ${texto.charAt()}`)
indice=prompt(`Ingrese un número positivo menor a ${texto.length}`)
console.log(`El caracter en esa posición es: ${texto.charAt(indice)}`)

//Método utilizando concatenación
console.log("Texto ingresado: " +texto)
console.log("El caracter en primer lugar es: "+texto.charAt())
indice=prompt("Ingrese un número positivo menor a "+texto.length)
console.log("El caracter en esa posición es: "+texto.charAt(indice))
```

#### Resultado en consola
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio9-1.JPG?raw=true)
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio9-2.JPG?raw=true)
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio9.JPG?raw=true)



## Ejercicio #10
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/Tarea6_Trabajo_En_Clase_Realizar_Los_Siguientes_20_Ejercicios_En_Javascript/10.png?raw=true)

#### Código
```javascript
var n_shows= prompt("Ingrese cuántos shows musicales ha visto en el último año")
console.log(`Shows vistos en el último año: ${n_shows}`)
n_shows >3
```

#### Resultado en consola
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio10-1.JPG?raw=true)
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio10.JPG?raw=true)



## Ejercicio #11
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/Tarea6_Trabajo_En_Clase_Realizar_Los_Siguientes_20_Ejercicios_En_Javascript/11.png?raw=true)

#### Código
```javascript
var fecha= parseInt(prompt("Ingrese una fecha formada por 8 números (DDMMAAAA)"))
console.log(`Fecha ingresada en formato DDMMAAAA: ${fecha}`)
//Método convirtiendo entero a string con la función String() dentro del console.log
console.log(`${(String(fecha)).slice(0,2)}/${(String(fecha)).slice(2,4)}/${(String(fecha)).slice(4,8)}`)
//Método convirtiendo entero a string con la función toString dentro del console.log
console.log(`${(fecha.toString()).slice(0,2)}/${(fecha.toString()).slice(2,4)}/${(fecha.toString()).slice(4,8)}`)
```

#### Resultado en consola
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio11-1.JPG?raw=true)
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio11.JPG?raw=true)



## Ejercicio #12
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/Tarea6_Trabajo_En_Clase_Realizar_Los_Siguientes_20_Ejercicios_En_Javascript/12.png?raw=true)

#### Código
```javascript
var numero= parseInt(prompt("Ingrese un número entero"))
console.log(`Número entero ingresado: ${numero}`)
numero%2==0
```

#### Resultado en consola
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio12-1.JPG?raw=true)
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio12.JPG?raw=true)



## Ejercicio #13
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/Tarea6_Trabajo_En_Clase_Realizar_Los_Siguientes_20_Ejercicios_En_Javascript/13.png?raw=true)

#### Código
```javascript
var edad=parseInt(prompt("Ingrese su edad"))
console.log(`Tu edad: ${edad}`)
var articulos=parseInt(prompt("Ingrese la cantidad de articulos comprados en una tienda"))
console.log(`Artículos comprados: ${articulos}`)
edad>18 && articulos>1
```

#### Resultado en consola
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio13-1.JPG?raw=true)
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio13-2.JPG?raw=true)
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio13.JPG?raw=true)




## Ejercicio #14
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/Tarea6_Trabajo_En_Clase_Realizar_Los_Siguientes_20_Ejercicios_En_Javascript/14.png?raw=true)

#### Código
```javascript
var frase= prompt("Ingrese una frase")
console.log(`Frase ingresada: ${frase}`)
frase.length%2 != 0
```

#### Resultado en consola
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio14-1.JPG?raw=true)
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio14.JPG?raw=true)



## Ejercicio #15
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/Tarea6_Trabajo_En_Clase_Realizar_Los_Siguientes_20_Ejercicios_En_Javascript/15.png?raw=true)

#### Código
```javascript
var palabra1=prompt("Ingrese una palabra")
console.log(`Primera palabra ingresada: ${palabra1}`)
var palabra2=prompt("Ingrese otra palabra")
console.log(`Segunda palabra ingresada: ${palabra2}`)
palabra1.length < palabra2.length
```

#### Resultado en consola
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio15-1.JPG?raw=true)
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio15-2.JPG?raw=true)
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio15.JPG?raw=true)



## Ejercicio #16
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/Tarea6_Trabajo_En_Clase_Realizar_Los_Siguientes_20_Ejercicios_En_Javascript/16.png?raw=true)

#### Código
```javascript
var nombre=prompt("Ingrese su nombre")
console.log(`Tu nombre: ${nombre}`)
var otro_nombre=prompt("Ingrese el nombre de otra persona")
console.log(`Otro nombre: ${otro_nombre}`)
nombre.charAt(0)==otro_nombre.charAt(0) || nombre.charAt(nombre.length -1) == otro_nombre.charAt(otro_nombre.length -1)
```

#### Resultado en consola
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio16-1.JPG?raw=true)
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio16-2.JPG?raw=true)
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio16.JPG?raw=true)



## Ejercicio #17
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/Tarea6_Trabajo_En_Clase_Realizar_Los_Siguientes_20_Ejercicios_En_Javascript/17.png?raw=true)

#### Código
```javascript
var numero=parseInt(prompt("Ingrese un número entero"))
console.log(`Número: ${numero}`)
console.log(`Valor absoluto: ${Math.abs(numero)}`)
```

#### Resultado en consola
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio17-1.JPG?raw=true)
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio17.JPG?raw=true)



## Ejercicio #18
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/Tarea6_Trabajo_En_Clase_Realizar_Los_Siguientes_20_Ejercicios_En_Javascript/18.png?raw=true)

#### Código
```javascript
var numero=parseInt(prompt("Ingrese un número"))
console.log(`Un número: ${numero}`)
var otro_numero=parseInt(prompt("Ingrese otro número diferente"))
console.log(`Otro número distinto: ${otro_numero}`)
//Método a través de condicionales
if (numero > otro_numero) {
	//document.write(numero);
	console.log(`${numero} es el mayor`)
} else {
	//document.write(otro_numero);
	console.log(`${otro_numero} es el mayor`)
}
//Método a traves de la función Math.max
console.log(`${Math.max(numero,otro_numero)} es el mayor`)
```

#### Resultado en consola
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio18-1.JPG?raw=true)
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio18-2.JPG?raw=true)
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio18.JPG?raw=true)



## Ejercicio #19
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/Tarea6_Trabajo_En_Clase_Realizar_Los_Siguientes_20_Ejercicios_En_Javascript/19.png?raw=true)

#### Código
```javascript
var letra=prompt("Ingrese una letra")
console.log(`Letra: ${letra}`)
if ((letra.length > 1) || (letra=='') || (!isNaN(letra))) {
	console.log("No se puede procesar el dato porque no ingresó una letra")
}else{ 
	var vocal = (/^[aeiou]$/i).test(letra);
	if (vocal==true){
    	console.log("Es vocal");
  	}else{
     	console.log("no es una vocal")
  	}
}
```

#### Resultado en consola
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio19-1.JPG?raw=true)
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio19.JPG?raw=true)



## Ejercicio #20
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/Tarea6_Trabajo_En_Clase_Realizar_Los_Siguientes_20_Ejercicios_En_Javascript/20.png?raw=true)

#### Código
```javascript
var n1 = prompt("Escribe un número")
console.log(`Primer número: ${n1}`)
var n2 = prompt("Escribe un segundo número")
console.log(`Segundo número: ${n2}`)
var n3 = prompt("Escribe un tercer número")
console.log(`Tercer número: ${n3}`)
//Método a través de condicionales
if (n1 < n2 && n1 < n3) {
	console.log(`Menor: ${n1}`)
} else if (n2 < n3 && n2 < n1) {
	console.log(`Menor: ${n2}`)
} else {
	console.log(`Menor: ${n3}`)
}
//Método a traves de la función Math.min
console.log(`Menor: ${Math.min(n1,n2,n3)}`)
```

#### Resultado en consola
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio20-1.JPG?raw=true)
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio20-2.JPG?raw=true)
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio20-3.JPG?raw=true)
![](https://github.com/JhonDanielGonzalez/Tarea6-Ejercicios-JavaScript/blob/main/solucion_por_consola/ejercicio20.JPG?raw=true)