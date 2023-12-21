Kod JS umieszczamy w odpowiednim znaczniku.
```html
<script>KOD JS</script>
<script src="skrypt.js"></script>
```

Składnia (*syntax*) JS jest następująca:
```js
//Tworzenie zmiennych
var gl; //deklaracja zmiennej globalnej
let lok; //zmienna lokalna
const stala; //stałą -> nie mozna zmieniać wartości

gl = 10; //przypisanie wartości
let lok2 = 10.4; //inicjalizacja zmiennej

const wynik = gl + lok2 + 20; //40.4

let zm1 = 10; //integer -> całkowita
let zm2 = 10.2; //float -> zmiennoprzecinkowa
let arr = [10, 20, 30]; //array ->
let obiekt = {id: 10, name: "Jan Kowalski"};
```

Komentarze w JS 
W JS mamy 2 rodzaje komentarzy: 
 - komentarz liniowy
 ```js
 let i = 2; //To jest inicjalizacja zmiennej lokalnej 
```

- komentarz blokowy , wieloliniowy:
```js
/*
Funkcja sum, której zadaniem jest zwrócenie sumy dwóch argumentów l1 i l2
*/
function add(l1, l2){
return l1 + l2;
}
```
