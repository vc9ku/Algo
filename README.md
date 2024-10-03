
//Exercice 1
function addition(a, b) {
    return a + b;
  }
  
  addition(2, 3)
  
  console.log(addition(2, 3))
  
  
  //Exercice 2
  function salutation(nom) {
    return "Bonjour " + nom;
  }
  
  
  console.log(salutation("Alice"))
  
  
  //Exercice 3
  
  function estPair(nombre) {
    if (nombre%2 == 0)
      return true
      else {
        return false
      }
  }
  
  console.log(estPair(4))
  console.log(estPair(7))
  
  
  //Exercice 4
  
  function aireRectangle(longeur, largeur) { 
    return longeur * largeur
  }
  
  console.log(aireRectangle(5, 3))
  
  
  //Exercice 5
  
function estMajuscule(chaine) {
  if (chaine === chaine.toUpperCase())
    return true
    else {
      return false
  }
}
console.log(estMajuscule("HELLO")); // Résultat attendu : true
console.log(estMajuscule("Hello")); // Résultat attendu : false


// Exercice 6

function maxDeuxNombres(a, b) {
  return b
}
console.log(maxDeuxNombres(5, 10)); // Résultat attendu : 10


// Exercice 7

function difference(a, b) {
  // Écrire le code ici
}
console.log(difference(10, 3)); // Résultat attendu : 7