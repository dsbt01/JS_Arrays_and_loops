# `20.2` Sigamos "mapeando"

El m茅todo `array.map()` llama a una funci贸n para cada valor en un arreglo y luego genera un nuevo arreglo con los valores modificados.

```js
incrementByOne = function (number) {
  return number + 1; 
}

let myArray = [1, 2, 3, 4];

myArray.map(incrementByOne); //devuelve [2, 3, 4, 5]
```


## 馃摑 Instrucciones:

1. Crea una funci贸n llamada `myFunction` que multiplique cada n煤mero por 3.

2. Usa la funci贸n `array.map()` para ejecutar la funci贸n `myFunction` a trav茅s de cada valor en el arreglo.

3. Almacena el nuevo arreglo en una variable llamada `newArray` y luego imprimes el nuevo arreglo con `console.log()`.

## 馃挕 Pista:

+ La funci贸n tomar谩 un par谩metro con el elemento original que se transforma y se agrega en el nuevo arreglo.

+ Recuerda que tu funci贸n debe devolver cada uno de los nuevos elementos que se almacenar谩n en el nuevo arreglo.

