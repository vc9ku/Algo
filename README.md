// Exercice 1

function addition(a, b) {
return a + b;
}
console.log(addition(2, 3)); // Résultat attendu : 5

// Exercice 2

function salutation(nom) {
return "Bonjour " + nom;
}
console.log(salutation("Alice")); // Résultat attendu : "Bonjour Alice"

// Exercice 3

function estPair(nombre) {
return nombre % 2 === 0;
}
console.log(estPair(4)); // Résultat attendu : true
console.log(estPair(7)); // Résultat attendu : false

// Exercice 4

function aireRectangle(longueur, largeur) {
return longueur \* largeur;
}
console.log(aireRectangle(5, 3)); // Résultat attendu : 15

// Exercice 5

function estMajuscule(chaine) {
return chaine === chaine.toUpperCase();
}
console.log(estMajuscule("HELLO")); // Résultat attendu : true
console.log(estMajuscule("Hello")); // Résultat attendu : false

// Exercice 6

function maxDeuxNombres(a, b) {
return a > b ? a : b;
}
console.log(maxDeuxNombres(5, 10)); // Résultat attendu : 10

// Exercice 7

function difference(a, b) {
return Math.abs(a - b);
}
console.log(difference(10, 3)); // Résultat attendu : 7

// Exercice 8

function convertirEnCelsius(fahrenheit) {
return (fahrenheit - 32) \* 5 / 9;
}
console.log(convertirEnCelsius(100)); // Résultat attendu : 37.7778

// Exercice 9

function estMajeur(age) {
return age >= 18;
}
console.log(estMajeur(20)); // Résultat attendu : true
console.log(estMajeur(16)); // Résultat attendu : false

// Exercice 10

function maxTroisNombres(a, b, c) {
return Math.max(a, b, c);
}
console.log(maxTroisNombres(3, 7, 5)); // Résultat attendu : 7
