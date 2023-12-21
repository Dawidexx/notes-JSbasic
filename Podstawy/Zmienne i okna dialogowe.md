*Zmienna to obszar w pamięci komputera , która przechowuje pewną wartość.*
W JS mamy 2 rodzaje zmiennych i stałą.
```js
let name = "Adam Kowalski"; // Zmienna lokalna (na chwile)
var suma = 12.4; // Zmienna globalna

var i = 20;
for(let i = 0; i<=10; i++){
console.log("Wartość i: "+i); //0->10
}
console.log("Wartość i:"+i) //nie pokaże wartości 10, która wynika z działania pętli a wartość 20 bo tyle wynosi zmienna globalna -> poza nawiasem klamrowym{}


```

Stała służy do przetrzymywania wartości niezmiennych np.:
```js
const VAT = 23; //VAT w PL wynosi 23%
var jablkaGolden = 6.2; //6.2zł netto
let ilosc = 5; //5kg
let jablkaGoldenVAT = ((jablkaGolden * ilosc) * VAT/100);
let cenaKoncowa = (jablkaGoldenVAT + jablkaGolden * ilosc);


// Wykorzystanie const do tzw. referencji 
const button = document.getElementById("przyciskWyslij");
button.addEventListener("click", function(e){
e.preventDefault(); //zatrzymanie akcji przełodowania strony
})


// Wykorzystanie const do deklaracji funkcji 
const funkcja = () =>{
console.log("JS jest prosty;)");
}
 funckja(); // uruchomienie, wywołanie działania funkcji

```
