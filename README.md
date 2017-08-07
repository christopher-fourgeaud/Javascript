# Javascript

## Les variables

### Déclarer une variable
var a;

console.log(a);

### Affecter une valeur à une variable

var a = valeur / "chaîne de caractère" / booléen( true / false );

===========================================================================

## Les conditions

#### Signification des Opérateurs

"==="	Egal à

"!=="	Différent de

"<" 	Inférieur à

"<="  	Inférieur ou égal à

">" 	Supérieur à

">=" 	Supérieur ou égal à

#### Opérateurs logiques
&&  = ET

||  = OU

!   = NON

### L'instruction if

if (condition) {

    // instructions exécutées quand la condition est vraie
    
}


### L'instruction else

if (condition) {

    // instructions exécutées quand la condition est vraie
    
}

else {

    // instructions exécutées quand la condition est fausse
    
}

### L'instruction switch

switch (expression) {

case valeur1:

    // instructions exécutées quand expression vaut valeur1
    
   break;
    
case valeur2:

    // instructions exécutées quand expression vaut valeur2
    
   break;
    
...

default:

    // instructions exécutées quand aucune des valeurs ne correspond
    
}

===========================================================================

### La boucle While 
La boucle while permet de répéter des instructions tant qu'une condition est vérifiée.

while (condition) {

    // instructions exécutées tant que la condition est vérifiée
    
}

### La boucle For

for (initialisation; condition; incrémentation) {

    // instruction executées tant que la condition est vérifiée
    
}

L'initialisation se produit une seule fois, au début de l'exécution.
La condition est évaluée avant chaque tour de boucle. Si elle est vraie, un nouveau tour de boucle est effectué. Sinon, la boucle est terminée.
L'incrémentation est réalisée après chaque tour de boucle.

===========================================================================

## Les objets

### Definir un constructeur

function Person(nom, prenom) {

    this.nom = nom;
    this.prenom = prenom;

   // Code du constructeur
   
}

