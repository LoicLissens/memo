# Syntaxe en js

## c'est quoi le JS ?

## Syntaxe 

## Array et méthodes
### C'est quoi ? Comment on le déclare ?
Un Array est un tableau 
### Array.some():
*Array.some()*, test si **Au moins un** élement du tableau remplis une conditions fournie.
* Valeur de retour: Booléan (true ou false).
* Structure: nomArray.some(Callback);
* Exemple :
	let  nomArray = [10,25,30];
	let  lol1  =  nomArray.some(el  =>  el  ===  10);
	console.log(lol1) // true
### Array.every():
*Array.every()*, test si **Tous ** les  élemenst du tableau remplisent  une conditions fournie.
* Valeur de retour: Booléan (true ou false).
* Structure: nomArray.every(Callback);
* Exemple :
	let  lol  = [11,25,30];
	let  lol1  =  lol.every(el  =>  el  >  10);
	console.log(lol1)// Renvois True
