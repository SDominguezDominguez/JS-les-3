# Opdracht beschrijving

Deze opdracht bestaat uit meerdere opdrachtjes om met functies, scope en for-loops te kunnen oefenen. Om de opdracht te maken kun je de opdracht clonen of downloaden naar jouw eigen computer.

Dit project bevat de volgende bestanden:

1. `functions-methods.js`
2. `functions-and-scope.js`

Zorg ervoor dat je de functies **altijd een waarde laat teruggeven**. Dit log je vervolgens in de console.

Dus niet:
```javascript
function example() {
  console.log('Hallo!');
}

example();
```

Maar wel zo:

```javascript
function example() {
  return 'Hallo!';
}

// OF we loggen wat er terugkomt uit de functie in de console
console.log(example());

// OF je slaat de uitkomst op in een variabele en stopt dát in de console.log():
const outcome = example();
console.log(outcome);
```

## Script runnen
Als je de code wil runnen kun je dit doen door het volgende in de terminal in te voeren:

`nodemon functions-methods.js`

Als je wisselt van bestand moet je nodemon eerst stoppen (ctrl + c voor zowel Windows als Mac) en dan opnieuw starten met de nieuwe bestandsnaam, zoals bijvoorbeeld:

nodemon `functions-and-scope.js`