# SES Patterns: Decorator

Oefening voor https://kuleuven-diepenbeek.github.io/ses-course/patterns/decorator

## Technologie

Dit is een [gradle project](https://kuleuven-diepenbeek.github.io/ses-course/dependency-management/).

## Opgave

1. Dit project bevat het wagenpark voorbeeld van de [labo noties](https://kuleuven-diepenbeek.github.io/ses-course/patterns/decorator/). Hier dien je de volgende dingen nog aan te wijzigen:
    - Voorzie in de `main()` methode een nieuwe decorator instantie en geef die mee met de factory. Kijk in de output wat er gebeurt.
    - Maak een nieuwe auto implementatie aan, `VWPolo`. Geef de decorator een Golf en Polo mee. Nu maken we plots iets hoger niveau budget wagens!
    - Voorzie een eigen, statische decorator klasse, genaamd `PoloGolfDecorator`, die altijd bovenstaande wagens (Polo en Golf) combineert. Wat zit er in de klasse? Hoe implementeer je `assemble()`?
2. Werk verder op opgave 1: bouw een nieuwe `Factory` in Zweden. Deze Factory in Zweden kan veel meer kleuren op het chassis spuiten dan de klassieke Factory. (Verzin iets anders in het `println()` statement). Wat als een klant een combinatie van deze factory, en de klassieke wenst? Maak een Decorator voor de factories in plaats van de wagens. Test deze in de `Main` klasse.


