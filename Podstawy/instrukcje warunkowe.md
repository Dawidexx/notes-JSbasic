instrukcje warunkowe służą do sprawdzania warunków np. *Czy jesteś pełnoletni(a)?*, *Czy powinieneś otrzymać rabat na zakupy?* 

Przykłady wykorzystania:
```html
<form action="#" method="post">
<input type="text" name="login" id="login" placeholder="Wpisz swój login"><br>
<input type="password" name="pas" id="pass" placeholder="Wpisz swoje hasło"><br>
<input type="submit" value="Zaloguj">
</form>
```

```js
const btnZaloguj = document.querySelector("input[type=submit]");
const inputLogin = document.querySelector("#login");
const inputPassword = document.querySelector("#pass");

]btnZaloguj.addEventListener("submit", (e)=>{
	e.preventDefault();
if(inputLogin.value==="dawid" && inputPassword.value === "12345"){
	alert("Cześć "+inputLogin.value+"!");
}
})
```